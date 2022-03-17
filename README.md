# bleutools
油猴脚本外部依赖  
`// @require      https://cdn.jsdelivr.net/npm/bleutools@1.0.1/bleutools.min.js`

界面xhr依赖  
`// @require      https://cdn.jsdelivr.net/npm/sweetalert2@11.1.0/dist/sweetalert2.all.min.js`  
`// @grant        GM_xmlhttpRequest`

例子  
- 1.提示信息：`bleu.swalInfo("🔴💬刷新页面，重新获取", '', 'center')`  
- 2.界面：`bleu.swalUI('WEBDAV画质', tools.configHtml(), '400px')`  
- 3.xhr：```bleu.XHR('MKCOL', `https://${bleuc.cip}/PanPlaylist/${flag}${tempPath}`, undefined, header, 'xml')```  
- 4.sleep：`bleu.sleep(1500);`
