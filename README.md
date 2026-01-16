[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=bansuk1216)](https://solved.ac/bansuk1216/)

## Open Source Contributions

- [spring-projects/spring-batch](https://github.com/spring-projects/spring-batch)
  - Fix StaxEventItemWriter resource switching within a transaction [#5177](https://github.com/spring-projects/spring-batch/pull/5177)
    - ClosedChannelException and FileChannel leak when switching resources multiple times within the same transaction [#5176](https://github.com/spring-projects/spring-batch/issues/5176)
  - Deprecate StepExecution convenience getters for JobExecution id and parameters [#5143](https://github.com/spring-projects/spring-batch/pull/5143)
    - Deprecate StepExecution convenience getters for JobExecution id and parameters [#5142](https://github.com/spring-projects/spring-batch/issues/5142)
  - Fix isolationLevelForCreate binding for Mongo job repository [#5141](https://github.com/spring-projects/spring-batch/pull/5141)
    - @EnableMongoJobRepository fails with Invalid transaction attribute token: [SERIALIZABLE] [#5105](https://github.com/spring-projects/spring-batch/issues/5105)
  - Fix restart position handling in AbstractPaginatedDataItemReader#jumpToItem [#5137](https://github.com/spring-projects/spring-batch/pull/5137)
    - The implementation of jumpToItem(int itemLastIndex) in AbstractPaginatedDataItemReader does not handle restart behavior correctly. [#5136](https://github.com/spring-projects/spring-batch/issues/5136)
  - Remove redundant assert in StoredProcedureItemReader [#5119](https://github.com/spring-projects/spring-batch/pull/5119)
  - Replace CopyOnWriteArrayList with ArrayList in PagingItemReaders [#5113](https://github.com/spring-projects/spring-batch/pull/5113)
    - Replace CopyOnWriteArrayList with ArrayList in JdbcPagingItemReader and JpaPagingItemReader for performance and correctness [#5112](https://github.com/spring-projects/spring-batch/issues/5112)
  - Fix incorrect resource closing order in AbstractCursorItemReader#doClose [#5110](https://github.com/spring-projects/spring-batch/pull/5110)
    - Incorrect resource cleanup order in AbstractCursorItemReader#doClose leads to inconsistent behavior [#5109](https://github.com/spring-projects/spring-batch/issues/5109)

- [spring-projects/spring-restdocs](https://github.com/spring-projects/spring-restdocs)
  - HTTP request snippet for PATCH, POST and PUT requests with no body has an incorrectly inferred Content-Type header [#1018](https://github.com/spring-projects/spring-restdocs/pull/1018)
    - HttpRequestSnippet incorrectly infers Content-Type for POST/PUT/PATCH requests without a body [#1017](https://github.com/spring-projects/spring-restdocs/issues/1017)
  - Remove redundant append in MockMvcResponseConverter [#1012](https://github.com/spring-projects/spring-restdocs/pull/1012)
