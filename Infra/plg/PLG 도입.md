# Loki  
* 아주 좋은 친구  
* 야무져  
![IMAGE](https://raw.githubusercontent.com/nogi-bot/resources/main/chatgptisgod/images/ea41732b-5522-4aed-b844-c6c0ca5bc66d-loki.png)  
  
![IMAGE](https://raw.githubusercontent.com/nogi-bot/resources/main/chatgptisgod/images/40ba640d-14aa-4d49-bdec-6e1868dccba9-prometheus.png)  
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
