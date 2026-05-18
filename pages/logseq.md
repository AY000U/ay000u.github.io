- [20 Logseq Features You Didn't Know Existed](https://www.youtube.com/watch?v=khNI-4r2wW0)
	-
- {{video https://youtu.be/khNI-4r2wW0?si=hTxx8ubiDJkGjJFc}}
	- {{youtube-timestamp 5:15}}
	- {{youtube-timestamp 7:40}} 查询功能 query
- {{query #}} 可以搜索此标签下的东西，适合日程表
  query-table:: true
  query-sort-by:: page
  query-sort-desc:: false
- [[draws/2025-07-09-03-02-17.excalidraw]]
-
- Logseq通过不同的状态来帮你区分任务的紧急程度，简单来说可以这样理解：
- **`TODO`**：需要做的任务。
- **`NOW`**：正在进行的任务，通常会固定在每日日志顶部提醒[](https://cloud.tencent.com.cn/developer/article/2182525?policyId=1004)。
- **`LATER`**：计划未来做的事[](https://cloud.tencent.com.cn/developer/article/2182525?policyId=1004)。
- **`DOING`**：进行中的任务，特点是会持续出现在后续的每日日志中，直到你把它标记完成。
- **`DONE`**：已完成的任务[](https://blog.csdn.net/zhzht19861011/article/details/146177595)。
- **`WAITING`**：等待外部反馈的任务。
- **`CANCELED`**：已取消的任务
  切换任务状态时，你可以通过重复按 `Ctrl` + `Enter` 来在同级状态之间快速循环[](https://blog.csdn.net/zhzht19861011/article/details/146177595)。
- Logseq通过不同的状态来帮你区分任务的紧急程度，简单来说可以这样理解：
- **`TODO`**：需要做的任务。
- **`NOW`**：正在进行的任务，通常会固定在每日日志顶部提醒[](https://cloud.tencent.com.cn/developer/article/2182525?policyId=1004)。
- **`LATER`**：计划未来做的事[](https://cloud.tencent.com.cn/developer/article/2182525?policyId=1004)。
- **`DOING`**：进行中的任务，特点是会持续出现在后续的每日日志中，直到你把它标记完成。
- **`DONE`**：已完成的任务[](https://blog.csdn.net/zhzht19861011/article/details/146177595)。
- **`WAITING`**：等待外部反馈的任务。
- **`CANCELED`**：已取消的任务。
  
  切换任务状态时，你可以通过重复按 `Ctrl` + `Enter` 来在同级状态之间快速循环[](https://blog.csdn.net/zhzht19861011/article/details/146177595)。
- **设置日期**：使用 `/date` 命令为任务设定到期日（Deadline）或日程（Scheduled），到期后会自动出现在你的日志页面提醒[](https://blog.csdn.net/zhzht19861011/article/details/146177595)。
- **使用 `QUERY` 功能**：Logseq可以通过简单的查询来汇总任务。例如，在一个新页面输入以下代码，就能汇总所有 `DOING` 状态的任务
	- {{query (todo doing)}}
-