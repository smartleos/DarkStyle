DarkStyle - IDE編輯器的黑色風格
=========

Dark theme of SharpDevelop 4.x and Visual Studio 2008/2010
--------

SharpDevelop 4.2.x 沒有提供匯出功能，XML設定檔裡面會包含很多其他的資料，所以放上來的只保留自訂色彩的區段（CustomizedHighlightingRules），下載後請依下述步驟更新顏色：

1. 開啟下載的SharpDevelopProperties.xml，選取以下區塊（第二行到倒數第二行），並複製到剪貼薄： 
 
        <SerializedValue name="CustomizedHighlightingRules">
            ...........
        </SerializedValue>
2. 開啟SharpDevelop執行目錄下的SharpDevelopProperties.xml，找到上述XML的區塊，置換為步驟1所複製起來的內容。

強烈建議升級 SharpDevelop 4.3.x，因為有提供編輯器色彩設定檔的匯入、匯出功能。下面 4.3 的設定檔後，到「Tools/Options/Text Editor/Hightlighting」下，按【Import hightlighting colors】即可匯入。

Visual Studio 2008/2010的設定檔，只有匯出「環境/字型及色彩」設定項目，所以可以直接在「檔案/工具/匯入匯出設定」中，匯入設定檔。