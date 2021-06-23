# Datasets Descriptions
 ## 1. flamingo-data:  
Consists of CSVs holding organisational data. Like ad-click records, store transactions, users, teams, etc.  
[**Schema**](https://d3c33hcgiwev3.cloudfront.net/_88da048d690b9eb23619a2f99b8d0373_UnderstandingtheCSVFilesGeneratedbytheScripts.pdf?Expires=1624579200&Signature=iPhZIi9QQCOnBTrFzDEPHaZ6~4Bje1Q4imUtVLR-elsCe-ipzELIDqK1WJXMNrqtMB3ZylXBwuwTT6vqlsQo~Ud3GkOntd3N3wc3wZZ6Nk5v3toTcu9HymV246BVTYFi3PPyCYoZD--WiBfqBh9RCpnrSUNAvPvig9ymukbnWq4_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

 ## 2. combined-data:  
Table is essentially a product of joins of some tables of the flamingo-data tables.  
Namely ```user-session.csv, buy-clicks.csv, and game-clicks.csv```  
Used for Classification.  
**Schema**  

| Column           | Description                                  |
| :--------------- | :------------------------------------------- |
| userid           | User ID                                      |
| userSessionid    | User session ID                              |
| team_level       | User’s team level                            |
| platformType     | Platform used by user                        |
| count_gameclicks | Total number of game clicks for user session |
| count_hits       | Total number of game hits for user session   |
| count_buyid      | Total number of purchases for user session   |
| avg_price        | Average purchase price for user session      |

## 3. chat-data:  
Consists of CSVs that capture the interactions between Users, Teams, ChatSessions, ChatItems.  
[**Schema**](https://d3c33hcgiwev3.cloudfront.net/_b0d40c785760aba59e98843b4ead5e80_UnderstandingtheSimulatedChatDataGeneratedbytheScripts.pdf?Expires=1624579200&Signature=N4NXuczw1~ZuQzNdi5pIhkBF~orvnjbHE~IkJzNTdGzbrdNB0yAv00KS50JyxI-uX1BLoj4jjHQMNX7aLVghE472Do-5xQZeQMFFqpdcM-vBs2g-FwQGSkVoVcEXQBomH5gzeondnlrL8HaVVC0-1RmiDOeUAaIiUJnenjbGhL0_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)