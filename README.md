# _WD_ERROR_GeneralError
Global Enum _         $_WD_ERROR_Success = 0, _        ; No error         $_WD_ERROR_GeneralError, _       ; General error         $_WD_ERROR_SocketError, _        ; No socket         $_WD_ERROR_InvalidDataType, _    ; Invalid data type (IP, URL, Port ...)         $_WD_ERROR_InvalidValue, _       ; Invalid value in function-call         $_WD_ERROR_SendRecv, _           ; Send / Recv Error         $_WD_ERROR_Timeout, _            ; Connection / Send / Recv timeout         $_WD_ERROR___UNUSED, _           ;         $_WD_ERROR_NoMatch, _            ; No match for _WDAction-find/search _WDGetElement...         $_WD_ERROR_RetValue, _           ; Error echo from Repl e.g. _WDAction("fullscreen","true") &lt;> "true"         $_WD_ERROR_Exception, _          ; Exception from web driver         $_WD_ERROR_InvalidExpression, _  ; Invalid expression in XPath query or RegEx         $_WD_ERROR_COUTNER ;  Global Const $aWD_ERROR_DESC[$_WD_ERROR_COUTNER] = [ _         "Success", _         "General Error", _         "Socket Error", _         "Invalid data type", _         "Invalid value", _         "Timeout", _         "No match", _         "Error return value", _         "Error TCPSend / TCPRecv", _         "Webdriver Exception", _         "Error TCPSend / TCPRecv", _         "Invalid Expression" _         ]
