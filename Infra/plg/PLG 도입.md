![IMAGE](https://raw.githubusercontent.com/nogi-bot/resources/main/chatgptisgod/images/fe9e92da-c10f-4253-bc87-be330f54e5b2-loki.png)  
  
![IMAGE](https://raw.githubusercontent.com/nogi-bot/resources/main/chatgptisgod/images/18f4aa75-a817-4d6d-b20b-8dbac5116649-prometheus.png)  
## PLG 성공!  
```java  
  private void logStartTilResults(List<NotionStartTILResult> notionStartTILResults) {
    log.info("After Notion StartTIL:\n{}",
        notionStartTILResults.stream()
            .map(result -> String.format(
                " - userId: %d, category: %s, title: %s, notionPageId: %s",
                result.userId(), result.category(), result.title(), result.notionPageId()))
            .collect(Collectors.joining("\n")));
  }  
```  
