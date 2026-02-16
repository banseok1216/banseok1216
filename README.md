[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=bansuk1216)](https://solved.ac/bansuk1216/)

## Open Source Contributions


### spring-projects/spring-batch

| PR | Description | Related Issue |
|---|---|---|
| [#5177](https://github.com/spring-projects/spring-batch/pull/5177) | Fix StaxEventItemWriter resource switching within a transaction | [#5176](https://github.com/spring-projects/spring-batch/issues/5176) ClosedChannelException and FileChannel leak when switching resources multiple times within the same transaction |
| [#5141](https://github.com/spring-projects/spring-batch/pull/5141) | Fix `isolationLevelForCreate` binding for Mongo job repository | [#5105](https://github.com/spring-projects/spring-batch/issues/5105) `@EnableMongoJobRepository` fails with `Invalid transaction attribute token: [SERIALIZABLE]` |
| [#5137](https://github.com/spring-projects/spring-batch/pull/5137) | Fix restart position handling in `AbstractPaginatedDataItemReader#jumpToItem` | [#5136](https://github.com/spring-projects/spring-batch/issues/5136) `jumpToItem(int itemLastIndex)` does not handle restart behavior correctly |
| [#5110](https://github.com/spring-projects/spring-batch/pull/5110) | Fix incorrect resource closing order in `AbstractCursorItemReader#doClose` | [#5109](https://github.com/spring-projects/spring-batch/issues/5109) Incorrect resource cleanup order leads to inconsistent behavior |
| [#5143](https://github.com/spring-projects/spring-batch/pull/5143) | Deprecate `StepExecution` convenience getters for `JobExecution` id and parameters | [#5142](https://github.com/spring-projects/spring-batch/issues/5142) Deprecate StepExecution convenience getters for JobExecution id and parameters |
| [#5119](https://github.com/spring-projects/spring-batch/pull/5119) | Remove redundant assert in `StoredProcedureItemReader` | - |
| [#5113](https://github.com/spring-projects/spring-batch/pull/5113) | Replace `CopyOnWriteArrayList` with `ArrayList` in paging item readers | [#5112](https://github.com/spring-projects/spring-batch/issues/5112) Performance and correctness improvement for `JdbcPagingItemReader` and `JpaPagingItemReader` |

### spring-projects/spring-restdocs

| PR | Description | Related Issue |
|---|---|---|
| [#1018](https://github.com/spring-projects/spring-restdocs/pull/1018) | Fix incorrectly inferred `Content-Type` for PATCH/POST/PUT requests with no body | [#1017](https://github.com/spring-projects/spring-restdocs/issues/1017) `HttpRequestSnippet` infers `Content-Type` incorrectly for bodyless write methods |
| [#1012](https://github.com/spring-projects/spring-restdocs/pull/1012) | Remove redundant append in `MockMvcResponseConverter` | - |


