LoaMusDoChaV90MS-Stable

--功能--
基於載入音樂MP3 和 輸出TXT為製作好的 音符時間位
透過實時按M進行錄製音符位的 Marker，
可以是人聲部份或整首歌的單音，不支援多重音、MIDI輸出
手殘按不淮，可以在錄製1整次後慢慢修改

--IPHONE使用--
請使用V74MS
只有最基本功能錄製和輸入
無法顯示上個鍵位綠標顯示、選取中途的 Marker
 需要下載 APP STORE 中的 HTML Viewer 才能使用
 >輸出方法
 使用HTML Viewer 輸出TXT時
 手動選取 copy 到IPHONE 的GOOGLE EXCEL
 在PC 中使用 NOTEPAD++ 把時間和鍵位間的空格，
 取代為\t (TAB空格)
    >格式的例子
    
6.278	AS3
6.417	AS3
6.603	AS3
7.023	AS3
7.208	AS3
 

--基本操作--
**第一次載入後請暫不用鍵盤SPACE，
而是用按鈕Spa進行播放
 -M 記錄音位 
 -Z X 前後選位
 -音鍵輸入
使用WASD FGHJ KW ETYU 為 鍵盤

滑鼠可選取 Marker 之間，再按 Z 或 X
以進行目標 Marker 的選取

I和O為設定 MAKER 選取時時間位置、
按P進行放左該位置

-鍵盤/按鍵
QBRVC
R為C4-B4範圍，QBVC為上下2層8音階，
等同整個鋼琴範圍

在不按QBVC時，都是永久在C4-B4範圍
用鍵盤輸入其他音階的音符
必須按住QBVC的其中一個
但畫面中的 按鈕 的不用，只是每次使用不同音階時
要自行再按，不像鍵盤自動回到C4-B4範圍


-- <> 5 I O P
根據IO的相約範圍，進行當前 Marker 的時間範圍前後選取
按P把選取範圍生成 以進行放大調較
  -- 進階用法
  如想不斷縮少就可以不斷按>
  或用X移到範圍外再按O和P
  --5
  為重置放大範圍到整個時間線
  

--修改部份--
按英文鍵上方的0鍵
可以把選取中的 Marker 進行刪除
如果要中途插入 Marker ，
在播放後按M錄後，
必須要按P
才能更新正確 對應位置 及 對置次序 選取

--進階功能--
1x 8x 30x 100x
為手機版選多少個後的 Marker 


--輸入方法--



--綠孤線--
為顯示上一個或下一個已輸入的位置
畫面也會顯示該音符的音名和按法
以使用家更易按下正確的一段音符
    >手機版
   因為弧線的畫版範圍未能弄好，位置顯示錯誤
   所以手機版暫不支援，但你仍可以使用 V74MS 的版本

**綠孤線是要連網的..因為要使用別人的數據庫 進行參數上的方便調整


--音效位置--
*請確保把上個檔的音效都放進同一個位置
手機版則無須放音檔
因為IPHONE無法載入，
取而代之是模擬音頻

--音樂不對位
如果你發現載入音樂錄鍵後
音位和人聲嚴重對不上(一段音、唱了幾個字後)
即表示你獲取音樂的時間碼出問題
 -- 解決方法
 使用Audition 輸出成FLAC 再轉回MP3
 每次的輸出界面中
 把採換率、聲道、位深度
 都調成與源相同


--版權
只建議使用者自娛自樂
把TXT成品公開
可能會被社交平台下架
更不建議放上YT，可能會被紅標移除帳戶
除非有其他社交平台像音遊的自由發燒友論壇





RelMakV10S
載入製作好的TXT
用I和O選取歌一句的範圍
按P輸出成對應UKULELE的單音位置
每個單音的多種按法都已顯示出來︳
把文字先複雜到NOTEPAD再複雜到EXCEL來進行存儲




i just make html from imprt mp3 to extract as midi, 
but this is not generate automatic you need hand by hand like midi but you don't need any midi device,

LoaMusDoChaV90MS-Frok_multiNoteV100MS.html
is the first step 
import mp3(any you want song), 
then press play button and empty area of mouse click,
when mp3 was play just press M key to record markers what instrument melody you want
after pressing all marker
use mouse press the head part 
use I and O as a starting marker point and ending marker
and press P as zoom in those group

Second Step 
modify more accurate timming for those marker
pressing L to switch a playback speed as 0.6
remaking the marker when it play 
use 0 as delete won't timing marker 
use Z X to select previous or next marker

Third Step
input the note in the selected marker
press ASDFGHJ as C to B note
WE TYU as C# to A#
QBVC as C2toC3 C5-C6 need hold to press with note
R as C4to C5 don't need to hold as default pressing any note
Fourth step
using < > to switch to next part of marker and repeating  Step2-4
firth step
pressing 8 to add more note in one marker
but you need use mouse to press the QBVC ASDFG....for adding 
to replace or clear just use press keybord key to replace  
final 
export as txt and using 
NOTE.to.midi.V025-stable.html

