# UnitTest
## Unit Test Framework – shunit2  
安裝[shunit2](https://github.com/kward/shunit2)  

主要測試用的工具是放在src中的shunit2  

測試用的函式必須是test開頭


shunit2提供了多種assert函式：  
assertEquals, assertNotEquals  
assertNull, assertNotNull  
assertTrue, assertFalse  

範例中的判斷式：  
`assertEquals [當測試失敗時所要顯示的訊息] [期望值] [實際值]`
