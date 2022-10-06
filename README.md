# b4x20221006
B4X實驗: 使用 B4j Print JavaFX8 LIB 製作 POS專用印表機的列印功能(票據機Receipt Print/貼紙機Label Print)


B4X實驗: 使用 B4j Print JavaFX8 LIB 製作 POS專用印表機的列印功能(票據機Receipt Print/貼紙機Label Print)
參考資料:
B4j Print JavaFX8 LIB 作者@stevel05 作者很認真!!
https://www.b4x.com/android/forum/threads/b4j-print-javafx8.49836/#post-310701


0.LIB 如何加
	#PackagerProperty : VMArgs = --add-opens  javafx.graphics/javafx.print=b4j
	#VirtualMachineArgs: --add-opens javafx.graphics/com.sun.javafx.print=ALL-UNNAMED


1.票據機Receipt Print/貼紙機Label Print 安裝Print Driver


