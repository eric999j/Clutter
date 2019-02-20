目標：3個月3老鳥+1新進人員快速on board  

# 中心思想    
新人需全程參與團隊的活動  

# 衝刺(Sprint):
與會者：🐷
目的：當團隊決定要哪些 Item 後，就著手去衝  
時間：2-4 week的開發活動，實務上不要多過2個禮拜  
產出：potentially shippable product increment，也就是說這個 sprint 所增加的軟體功能如果客戶馬上就要的話，要可以交付給客戶  
前一天產出：Sprint demo agenda  
Sprint 結束前一天（或sprint demo meeting  前一天中午 12:00 之前）  
SM 要寫出 sprint demo 的議程表，並寄給 Scrum Team 與其他有興趣的輔助角色人員  
此議程表包含所有要 demo 的項目，以及每一個 demo 項目要花多少時間，由誰負責 demo  
所以當 Developer 收到該議程表時，就可以準備明天要 demo 的資料  

# 衝刺規劃會議(Sprint Planning Meeting):挑選這個 sprint 所要開發的需求（stories）  
與會者：🐷   
目的：強調團隊成員之間的對話  
時間：4-8hr每個 Sprint 開發活動的第一天  
產出：Spring Backlog（以 story 的方式撰寫，這個 Sprint 會盡力完成的 Item List) 跟Info Page(SM寫的文件，要給Scrum Team 以及其他有興趣的輔助角色人員,讓他們知道一個新的 sprint 已經開始了)  
Info Page要寫到：  
sprint goal,列出這個 sprint 所要施工的   
stories，sprint 開始與結束時間  
以及團隊成員  

(1)挑選這個 sprint 所要開發的需求（stories）  
(2)逐一將每一個 stories 細分為若干個 task（施工項目），並且估算完成每一個 task 所需的時間（以小時計算）  

Sprint Planning Meeting參考：  
http://teddy-chen-tw.blogspot.com/2012/01/scrum-5-sprint-planning-meeting.html  

# 每日站立會議(Daily Scrum Meeting):  
與會者：🐷except PO  
目的：一個重新規劃會議，讓團隊資訊同步並修正達成sprint目標，會議通常以站立方式進行，為了長話短說  
時間：15min之內舉辦完畢的活動(看team大小斟酌)，一分鐘簡短介紹自己做什麼，做不完會有跡象修正  
產出：Potentially Shippable Product Increement用於Demo Meeting  
會議中團隊成員報告三件事情：  
(1)昨天做了什麼以協助團隊達成sprint目標  
(2)今天準備做什麼以協助團隊達成sprint目標  
(3)有沒有遇到任何阻礙團隊達成sprint目標  
Daily Scrum參考：  
http://teddy-chen-tw.blogspot.com/2012/01/scrum-7daily-scrum.html   

# 產品待辦清單精煉會議(Product Backlog Refinement/Product Backlog Grooming/PBR Meeting):
與會者：🐷  
目的：讓 PO 與開發團隊來檢視 Product Backlog裡面的項目  
時間：4-8hr 每個 Sprint 抽出 5%-10%  
然後挑選一些下一個 sprint 準備要施工的 stories  

# 衝刺檢視會議(Sprint Review Meeting/Demo Meeting):Sprint檢視會議，開發團隊要展示本此所完成的功能給利益相關者
與會者：🐷,🐔  
目的：讓 PO 確認這些 story 開發的功能是否符合客戶期待  
時間：2-4hr Sprint 結束的那一天會舉辦此會議  
產出：Requirement Feedback更新Product Backlog  
展示團隊在此 sprint 中所完成的每一個 story，是要可用的軟體才算產出。不準備Powerpoint或其他簡報，單純就軟體操作取得回饋   
如果不符合則可以在之後的 sprint 加以修正（此為回饋機制的意義，有錯則改之）  
由於每個 sprint 週期很短（一般 Scrum 團隊採用 2 週至 4 週的 sprint），所以可以避免傳統開發專案在專案晚期客戶才發現問題但卻沒時間加以修正的困境
Sprint Demo參考：  
http://teddy-chen-tw.blogspot.com/2012/01/scrum-7sprint-demo-meeting.html  

# 衝刺回顧會議(Retrospective/Sprint Retro Meeting):Sprint回顧會議，Scrum Master有問題這時候提出檢討，並列action items
與會者：🐷except PO  
目的：針對這個 Sprint 團隊的工作模式檢討與改善『軟體開發流程』最後團隊討論出改善行動方案（action plan），定出下個 Sprint 改善事項(或是連續若干個 sprints）中實施此改善項目  
時間：1.5-3hr Sprint Review 後  
產出：Process Improvement Feedback 改善行動方案更新Product Backlog跟Sprint summary report(SM準備，包含對於本次 sprint 所完成功能的簡述：
完成多少個 story points  
團隊成員在 sprint retrospective meeting 中所列出好的以及有待改善的1-3點  
改善行動計畫)將此文件寄給Scrum Team 以及其他有興趣的輔助角色人員，讓他們知道這個 sprint 已經正式結束了  
通常改善行動方案例如，30% 的 tasks 都要採用 pair programming 的方式施工，或是 build 一次軟體的時間要縮短為 10 分鐘等等  
在這個活動中，團隊成員們探討  
(1) 那些開發作法是好的，應該要繼續維持下去。例如，有導入持續整合，或是有持續做 pair programming  
(2) 有那些與開發流程有關的地方沒有做好需要改善的。例如，自動化單元測試做的不夠多，或是測試硬體設備不夠  
(3) 擬定改善計畫(action plan)  
Retrospective參考：  
http://teddy-chen-tw.blogspot.com/2012/01/scrum-9retrospective-meeting.html  

# Scrum雙重回饋機制
就是衝刺檢視會議(對外)跟衝刺回顧會議(對內)

# 由新人總結會議摘要，mentor針對摘要提問  
mentor 最好已經在公司半年以上，並樂於栽培新人，新人也可以有個清單跟mentor反應，且清單需有優先順序跟dead line  
公司新人訓還是第一要務

# [第一個月]  
每一周都有一位 mentor 跟菜鳥 pair，建議每一周換一位 mentor 進行 pair    
主要由 mentor 撰寫代碼，菜鳥遇到不理解的部份，可即時或記下等會發問    
mentor 寫一段落後，讓菜鳥發問，回答疑問，反問相關問題。菜鳥沒有疑問，就由 mentor 提問    

# 第一個月最後一週  
菜鳥整理這個月的 4L (Liked – Learned – Lacked – Longed For)    
由 mentors 給予反饋(好的、待改善)  
菜鳥擬出待改善的行動計畫    

# [第二個月]  
菜鳥挑一位適合的 mentor 一起 pair 一個月  
mentor 可適時詢問菜鳥，打算怎麼寫。如果菜鳥沒問題，mentor 就問問題  

# 第二個月最後一次 retrospective 
由菜鳥對團隊提出一個 CSS (一件 Continue, 一件 Stop, 一件 Start) 的建議  
由 mentor 給予反饋（好的、待改善）  
菜鳥擬出待改善的行動計畫  

# [第三個月]
依據 backlog item 跟團隊其他人進行 pair programming  
建議由菜鳥主動說明打算怎麼做，也先由菜鳥來寫，mentor 即時引導、提問、建議、示範  

# 最後一週，菜鳥針對產品(or 專案) domain、系統架構/共用元件、開發規範（含團隊公約、DoD等等...）
協作流程，做一個簡報，用以呈現菜鳥對這些的理解程度。簡報只須報告重點，由與會者提問，重點在促進溝通與交流  
每個跟菜鳥 pair 過的成員，最後都須給菜鳥評分（試用期團隊接受程度）、反饋、建議  
整理出菜鳥 top 1~3 的待辦事項（先 grouping post-it, 接著團隊成員投票），當作後續加強或學習方針  

# 參考資料
https://dotblogs.com.tw/hatelove/2019/02/14/rookie-strategy-pair-programming  
http://teddy-chen-tw.blogspot.com/2011/12/scrum-1.html  
https://funevo.com/2015/06/27/scrum-agile-project-management-software-development  
