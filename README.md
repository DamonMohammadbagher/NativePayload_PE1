# NativePayload_PE1
### NativePayload_PE1 , Injecting Meterpreter Payload bytes into local Process via Delegation Technique + in-memory with delay Changing RWX to X or RX or (both), simple Technique to bypass some Anti-viruses

Note: tested on WIN10 + WinDefender [update 2023/1/10]

Simple Technique to Load Assembly/Bytes into local process (in-memory) via C# Delegation + Native APIs and Bypassing Anti-viruses ;), some part of code changed via [D]elegate Techniques which i called [Technique ;D] to change some behavior of code (also change source code) and ... 

note: as pentester you really need to change your own codes sometimes very fast , these codes changed and again worked very well and as security researcher this is really fun to find out new method/codes to bypass AVs always ;D

Method is not really new but C# code a little bit is ;D [since 2022 i used this], changing RWX to X and after 2 min to RX ;D 

#### Note: so in my opinion playing with R W X to X or sometimes to RX or (both) will help you to avoid get red-flag via AVs, so changing default + delays will help you to confuse AVs sometimes

### NativePayload_PE2 , Injecting Meterpreter Payload bytes into local Process via Delegation Technique + in-memory with delay Changing RWX to X only, simple Technique to bypass some Anti-viruses

Note: .NET 4.0 or 4.5 Tested

Article: https://www.linkedin.com/pulse/2-simple-c-techniques-bypassing-anti-virus-damon-mohammadbagher/

Article: https://damonmohammadbagher.github.io/Posts/22Jan2023x.html


Usage: 
    
     NativePayload_PE1.exe "meterpreter/cobaltstrike payload"
     example: NativePayload_PE1.exe "fc,48,e8,00,....."
     
Usage: 
    
     NativePayload_PE2.exe "meterpreter/cobaltstrike payload"
     example: NativePayload_PE2.exe "fc,48,e8,00,....."     


### NativePayload_PE1 steps
   ![](https://github.com/DamonMohammadbagher/NativePayload_PE1/blob/main/pic/_x1.png)
   
### NativePayload_PE1 steps
   ![](https://github.com/DamonMohammadbagher/NativePayload_PE1/blob/main/pic/_x2.png)
   
### NativePayload_PE1 steps
   ![](https://github.com/DamonMohammadbagher/NativePayload_PE1/blob/main/pic/_x3.png)
   
-------------------------   

### NativePayload_PE2 steps
   ![](https://github.com/DamonMohammadbagher/NativePayload_PE1/blob/main/pic/pe2.png)   

### NativePayload_PE2 vs ETW tools
   ![](https://github.com/DamonMohammadbagher/NativePayload_PE1/blob/main/pic/pe2_blueteaming_tool.png)   
<p><a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/DamonMohammadbagher/NativePayload_PE1/"/></a></p>
