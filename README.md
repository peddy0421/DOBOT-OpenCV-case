# DOBOT-OpenCV-case
結合了openCV、DOBOT小手臂、XMOS、樹梅派、Arduono、輸送帶

可透過聲控(xmos) 或 Arduino 啟動整體程序。
透過視覺(Opencv) 辨識顏色方塊，將其座標紀錄在PC中，
PC comport的方式傳送訊號給dobot，因dobot上有io可以控制輸送帶將方塊移動到Dobot前
再透過剛剛記錄到的座標將手臂移置將方塊吸取。
