# Lodop Debug
Lodop标签打印调试页面
1. 安装打印控件：CLodop_Setup_for_Win32NT.exe；
2. 使用360浏览器，极速模式；
3. 打开[Lodop打印Debug页面](https://zerothdream.github.io/Lodop-Debug/LodopPrintDebug.html)；
4. 输入需调试的打印指令，如：
```
LODOP.PRINT_INITA(0,-1,\"60.01mm\",\"40mm\",\"\");
LODOP.SET_PRINT_PAGESIZE(1,600,400,\"CreateCustomPage\");
LODOP.ADD_PRINT_TEXT(15,10,203,58,\"------- 开始打印 -------\");
LODOP.SET_PRINT_STYLEA(0,\"FontName\",\"微软雅黑\");
LODOP.SET_PRINT_STYLEA(0,\"FontSize\",13);
LODOP.SET_PRINT_STYLEA(0,\"Bold\",1);
LODOP.SET_PRINT_STYLEA(0,\"Alignment\",2);
LODOP.ADD_PRINT_TEXT(45,10,203,58,\"数量：6\");
LODOP.SET_PRINT_STYLEA(0,\"FontName\",\"微软雅黑\");
LODOP.SET_PRINT_STYLEA(0,\"FontSize\",12);
LODOP.SET_PRINT_STYLEA(0,\"Bold\",1);
LODOP.SET_PRINT_STYLEA(0,\"Alignment\",2);
LODOP.ADD_PRINT_TEXT(70,10,203,58,\"芳草依依\");
LODOP.SET_PRINT_STYLEA(0,\"FontName\",\"微软雅黑\");
LODOP.SET_PRINT_STYLEA(0,\"FontSize\",12);
LODOP.SET_PRINT_STYLEA(0,\"Bold\",1);
LODOP.SET_PRINT_STYLEA(0,\"Alignment\",2);
LODOP.PRINT();
LODOP.PRINT_INITA(0,-1,\"60.01mm\",\"40mm\",\"\");
LODOP.SET_PRINT_PAGESIZE(1,600,400,\"CreateCustomPage\");
LODOP.ADD_PRINT_TEXT(12,0,200,24,\"大时代  2 大时代\");
LODOP.SET_PRINT_STYLEA(0,\"FontName\",\"微软雅黑\");
LODOP.SET_PRINT_STYLEA(0,\"FontSize\",10);
LODOP.SET_PRINT_STYLEA(0,\"Alignment\",2);
LODOP.SET_PRINT_STYLEA(0,\"Bold\",1);
LODOP.ADD_PRINT_TEXT(12,200,30,24,\"G\");
LODOP.SET_PRINT_STYLEA(0,\"FontName\",\"微软雅黑\");
LODOP.SET_PRINT_STYLEA(0,\"FontSize\",10);
LODOP.SET_PRINT_STYLEA(0,\"Alignment\",1);
LODOP.SET_PRINT_STYLEA(0,\"Bold\",1);
LODOP.ADD_PRINT_TEXT(32,0,180,24,\"19187 白色 155/80A\");
LODOP.SET_PRINT_STYLEA(0,\"FontName\",\"微软雅黑\");
LODOP.SET_PRINT_STYLEA(0,\"FontSize\",10);
LODOP.SET_PRINT_STYLEA(0,\"Alignment\",2);
LODOP.SET_PRINT_STYLEA(0,\"Bold\",1);
LODOP.ADD_PRINT_BARCODE(60,12,204,60,\"128A\",\"2906795680004534\");
LODOP.SET_PRINT_STYLEA(0,\"FontSize\",7);
LODOP.SET_PRINT_STYLEA(0,\"Alignment\",2);
LODOP.SET_PRINT_STYLEA(0,\"Horient\",2);
LODOP.SET_PRINT_STYLEA(0,\"Vorient\",1);
LODOP.ADD_PRINT_TEXT(124,20,200,24,\"0004534\");
LODOP.SET_PRINT_STYLEA(0,\"FontName\",\"微软雅黑\");
LODOP.SET_PRINT_STYLEA(0,\"FontSize\",10);
LODOP.SET_PRINT_STYLEA(0,\"Alignment\",2);
LODOP.SET_PRINT_STYLEA(0,\"Bold\",1);
LODOP.SET_PRINT_STYLEA(0,\"LetterSpacing\",3);
LODOP.ADD_PRINT_TEXT(140,20,180,15,\"此标签为售后凭证,请务必保留\");
LODOP.SET_PRINT_STYLEA(0,\"FontSize\",7);
LODOP.PRINT();
```
6. 操作页面中的按钮，其中 Print - 打印、Preview - 预览、Copy - 复制当前打印指令、Clear - 清除当前文本框中的内容。
