# Penguin-Game
透過unity的ml-agent，訓練企鵝遊戲自動遊玩。    
參考Immersive Limit的youtube教學：Unity ML Agents Tutorial - Penguins 🐧 (FULL WALKTHROUGH)。    
https://www.youtube.com/watch?v=axF_nHHchFQ    
需使用python3.6，參照unity ml-agents官方文件下載步驟，使用ml-agents-0.8.2。     
[*在training過程中有小bug，估計是ml agent版本問題，待修改。 ]   

# ml-agents中的Agent程式碼重點
* Heuristic()會輸出actions
* CollectObservations()會接收環境的觀察值，參數的數量為vector observation的space size
* AgentAction() function assigns a reward to the Agent
* 透過agent中的Behavior Parameters 紀錄環境與控制action
