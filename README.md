DarkStyle
=========

Dark theme of SharpDevelop 4.x and Visual Studio 2008/2010
--------
先寫中文版，英文版後補。

SharpDevelop因為XML裡面會包含很多其他的資料，所以放上來的只保留自訂色彩的區段（CustomizedHighlightingRules），下載後請依下述步驟更新顏色：

1. 開啟下載的SharpDevelopProperties.xml，選取以下區塊（第二行到倒數第二行），並複製到剪貼薄：
  <SerializedValue name="CustomizedHighlightingRules">
		...........
	</SerializedValue>
2. 開啟SharpDevelop執行目錄下的SharpDevelopProperties.xml，找到上述XML的區劃，置換為步驟1所複製起來的內容。

Visual Studio 2008/2010的設定檔，只有匯出「環境/字型及色彩」設定項目，所以可以直接匯入。