<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
 <style>
 body{
   margin-top:40px
 }
   
 #inpt{
   margin-left:120px;
   width:120px;
   height:30px;
   border:2px solid yellow;
   border-radius:15px;
   margin-bottom:10px
 }
 #question{
   margin-right:80px;
   
 }
   }
   #myMenuL{
     background-color:bisque;
     border:2px solid black;
     width:350;
     height:550px;
     display:flex;
     flex-direction:column;
     font-family:monospace;
     border-radius:25px
    }
   #myMenuL2{
     margin-left:150px;
     background-color:#222;
     border:1px solid black;
     width:180px;
     height:400px;
     font-family:monospace;
     border-radius:50px;
     margin-top:25px
    }
    #mulaiMyMenuL{
      font-size:25px;
      margin:23px;
      width:150px;
      height:50px;
      border-radius:50px;
      font-weight:bolder;
      background-color:yellow;
      border:1px solid white;
      margin-left:20px;
    }
    #myMenuUClick{
      font-size:25px;
      margin:23px;
      width:110px;
      height:40px;
      border-radius:15px;
      font-weight:bolder;
      background-color:yellow;
      border:2px solid black;
      margin-left:20px;
      margin-top:3px;
      
    }
    #myMenuUClick:hover{
      font-size:25px;
      margin:23px;
      width:110px;
      height:40px;
      border-radius:15px;
      font-weight:bolder;
      background-color:aqua;
      border:2px solid black;
      margin-left:20px;
      margin-top:3px;
      color:red;
    }
    #mulaiMyMenuL:hover{
      font-size:25px;
      margin:23px;
      width:140px;
      height:50px;
      border-radius:50px;
      font-weight:bolder;
      background-color:white;
      border:2px solid yellow;
      margin-left:20px;
    }
    #cekPeringkatMyMenuL{
      font-size:25px;
      margin:23px;
      width:150px;
      height:80px;
      border-radius:50px;
      font-weight:bolder;
      background-color:pink;
      border:1px solid white;
      margin-left:20px;
    }
    #cekPeringkatMyMenuL:hover{
      font-size:25px;
      margin:23px;
      width:140px;
      height:80px;
      border-radius:50px;
      font-weight:bolder;
      background-color:white;
      border:2px solid pink;
      margin-left:20px;
    }
    #tentangMyMenuL{
      font-size:25px;
      margin:23px;
      width:150px;
      height:85px;
      border-radius:50px;
      font-weight:bolder;
      background-color:green;
      color: white;
      border:1px solid white;
      margin-left:20px;
      
    }
    #tentangMyMenuL:hover{
      font-size:25px;
      margin:23px;
      width:140px;
      height:85px;
      border-radius:50px;
      font-weight:bolder;
      background-color:white;
      color: black;
      border:2px solid green;
      margin-left:20px;
      
    }
    #judulMyMenuL{
      color:black;
      font-size:25px;
      text-decoration:underline;
    }
 #myMenuU{
   background-color:#222;
   border:3px solid black;
   height:310px;
   width:250px;
   font-family:monospace;
   font-weight:bolder;
   font-size:19px;
   box-shadow:0 0 6px black;
   color:white;
   border-radius:60px;
 }
 label{
   font-variant:small-caps;
   fomt-size:23px
 }
 #myMenuU1{
   margin-top:2px;
   border:1px solid black;
   height:25px;
   font-family:monospace;
   font-weight:bolder;
   font-variant:small-caps;
 }
 #myMenuU2{
   margin-top:2px;
   border:1px solid black;
   height:25px;
   font-family:monospace;
   font-weight:bolder;
 }
 label{
   font-size:28px;
   font-family:monospace;
 }
 #myysoal{
   text-align:center;
   background-color:#222;
   width:310px;
   color:white;
   padding-top:1px;
   border:2px solid black;
   border-radius:50px;
 }
 #myynilai{
   background-color:yellow;
   width:200px;
   padding-top:1px;
   padding-bottom:10px;
   border:1px solid black;
   border-radius:12px;
 }

 #disRank{
   background-color:skyblue;
   font-family:monospace;
   font-variant:small-caps;
   font-size:21px;
   padding-top:10px;
 }
 #backMenu, #backMenuInti, #hapusData,#btnAbout{
   width:85px;
   height:40px;
   border-radius:30px;
   margin-left:240px;
   margin-bottom:0px;
   font-size:18px;
   font-variant:small-capt;
   border:1px solid black;
   background-color:gold;
   font-weight:bolder;
 }
 #backMenu:hover, #backMenuInti:hover, #hapusData:hover, #btnAbout:hover{
   width:83px;
   height:38px;
   border-radius:30px;
   margin-left:240px;
   margin-bottom:0px;
   font-size:18px;
   font-variant:small-capt;
   border:1px solid black;
   background-color:red;
   font-weight:bolder;
 }
 #tingkatKesulitan{
   display:flex;
   flex-direction: column;
   
   font-size: 45px;
 }
#easy, #medium, #hard{
  font-variant: small-caps;
  font-size: 31px;
  width:130px;
  height:80px;
  margin:12px;
  border-radius:20px;
  background-color: green;
  color:white;
  border: 2px solid black;
  
}
#easy:hover, #medium:hover, #hard:hover{
  font-variant: small-caps;
  font-size: 31px;
  width:120px;
  height:78px;
  margin:12px;
  border-radius:20px;
  background-color: lime;
  color:black;
  border: 2px solid black;
}
#tingkatKesulitan{
  background-color: tomato;
  border:2px solid black;
  width:50%;
}
#displayGO{
  background-color: #222;
  padding-top:7px;
}
#displayGO2{
  background-color: white;
  width:80%;
  height:60%;
}
#btnRst{
  background-color: white;
  border:2px solid red;
  width:110px;
  height:65px;
  font-size: 40px;
  font-weight:bolder;
  font-family: monospace;
  border-radius: 30px;
}
#btnRst:hover{
  background-color: red;
  border:2px solid red;
  color:white;
  width:100px;
  height:60px;
  font-size: 50px;
  font-weight:bolder;
  font-family: monospace;
  border-radius: 30px;
}
#maker2{
  background-color:#222;
  color:white;
  width:90%;
  height:90%;
  margin-left:14px;
  border-radius:23px;
  box-shadow:0 0 12px white;
}
#maker{
  background-color:green;
  padding-top:2px;
  padding-bottom:2px;
  border-radius:23px;
  font-family:monospace;
  font-size:16px
}
#maker3{
  background-color:yellow;
  width:70%;
  border-radius:30px;
  font-variant:small-caps;
  color:black;
  font-family:arial;
  
}

 </style>
<body>
  <div id="maker">
    <div id="maker2">
      <center>
        <div id="maker3">
      <h2>About the Game</h2>
        </div>
      <h3><span style=' border: 1px solid white; color:white; background-color:green'>Game quiz </span> bertingkat ini dibuat pada <span style=' border: 1px solid white; color:white; background-color:green'>tgl 12 agustus 2024 - 25 agustus 2024 </span> secara bertahap. silahkan hubungi <span style=' border: 1px solid white; color:white; background-color:green'>email </span> : <span style=' border: 1px solid white; color:white; background-color:green'>luckywahyu050@gmail.com </span> untuk meminta tutorial menganti soal. diharapkan setiap orang dengan <span style=' border: 1px solid white; color:white; background-color:green'>keahlianya </span> masing-masing bisa bermanfaat untuk generasi selanjutnya.</h3>
         <button id="btnAbout">kembali</button>
      </center>
     
    </div>
  </div>
  <div id="tingkatKesulitan">
    <button id="easy">Easy</button>
    <button id="medium">Medium</button>
    <button id="hard">Hard</button>
    <button id="backMenuInti">Kembali</button>
  </div>
  <div id="disRank">
    <button id="backMenu">Kembali</button>
    <h2 style="margin-top:0px">Daftar  Nilai</h2>
    <h3 id="textRank"></h3>
    <button id="hapusData">HAPUS</button>
  </div>
  <div id="intiGame">
     <h4 id="display" style="font-family:monospace;text-align:center">Jawaban benar</h4>
  <div id="myynilai">
     <h2 id="skor"></h2>
     <h1 id="prmtr"></h1>
       <div id="myysoal">
          <h1 id="question"></h1>
          <input type="number" placeholder="masukan jawaban" id="inpt">
       </div>
     <h3 id="timer"></h3>
     <button id="tekan">TEKAN</button><br>
     
  </div>
  </div>
  <div id="myMenuL">
    <h2 id="judulMyMenuL">Hallo selamat datang</h2>
     <div id="myMenuL2">
       <div id="btn1">
         <button id="mulaiMyMenuL">Mulai Quiz</button>
       </div>
       <div id="btn2">
         <button id="cekPeringkatMyMenuL">Cek peringkat </button>
       </div>
       <div id="btn3">
         <button id="tentangMyMenuL">About the Game</button>
       </div>
    </div>
    
  </div>
  <center>
  <div id="displayGO">
    <div id="displayGO2">
     <h1 id="tamat" style="color:red;font-variant:small-caps;text-shadow:0 0 3px red;text-decoration:underline black">Upss Anda Kalah</h1>
     <h2 id="tamat2" style="color:red; font-variant:small-caps; text-shadow:0 0 12px red ">Game Over</h2>
    </div>
     <H3 id="textNG"></H3>
     <h4 style="color:white;margin-bottom:2px">Simpan dan Main lagi</h4>
     <button id="btnRst">🔄</button>
  </div>
  <div id="myMenuU">
    <br><br>
    <label>Your Name</label><br>
    <input id="myMenuU1"><br><br>
    <label>Hobby</label><br>
    <input id="myMenuU2"><br><br>
    <button id="myMenuUClick">SELESAI</button>
  </div>
  </center>
  <script>
    let tamat=document.getElementById("tamat")
    let tamat2=document.getElementById("tamat2")
    let btnAbout=document.getElementById("btnAbout")
    let maker3=document.getElementById("maker3")
    let maker2=document.getElementById("maker2")
    let maker=document.getElementById("maker")
    let btnRst=document.getElementById("btnRst")
    let textNG=document.getElementById("textNG")
    let tingkatKesulitan=document.getElementById("tingkatKesulitan")
    let easy=document.getElementById("easy")
    let medium=document.getElementById("medium")
    let hard=document.getElementById("hard")
    let hapusData=document.getElementById("hapusData")
    let backMenuInti=document.getElementById("backMenuInti")
    let backMenu=document.getElementById("backMenu")
    let disRank=document.getElementById("disRank")
    let textRank=document.getElementById("textRank")
    let displayGO2=document.getElementById("displayGO2")
    let displayGO=document.getElementById("displayGO")
    let myMenuUClick=document.getElementById("myMenuUClick")
    let myMenuU2=document.getElementById("myMenuU2")
    let myMenuU1=document.getElementById("myMenuU1")
    let myMenuU=document.getElementById("myMenuU")
    let intiGame=document.getElementById("intiGame")
    let tentangMyMenuL=document.getElementById("tentangMyMenuL")
    let cekPeringkatMyMenuL=document.getElementById("cekPeringkatMyMenuL")
    let mulaiMyMenuL=document.getElementById("mulaiMyMenuL")
    let judulMyMenuL=document.getElementById("judulMyMenuL")
    let myMenuL=document.getElementById("myMenuL")
    let skor=document.getElementById("skor")
    let prmtr=document.getElementById("prmtr")
    let question=document.getElementById("question")
    let inpt=document.getElementById("inpt")
    let timer=document.getElementById("timer")
    let tekan=document.getElementById("tekan")
    let display=document.getElementById("display")
    
    intiGame.style.display="none"
    myMenuL.style.display="none"
    btn1.style.display="none"
    btn2.style.display="none"
    btn3.style.display="none"
    
    tekan.addEventListener("click",function(){
           kerjakanQuiz()
           parameter()
           addSoal()
           gameOverDanSkor()
           tampSoal()
           indek++
           inpt.value=""
    })
    
    if(localStorage.getItem("data1")==null){
      localStorage.setItem("data1","[]")
    }
    function penyimpanan(){
      var myData=JSON.parse(localStorage.getItem("data1"))
      myData.push(`<span style='color:blue;font-size:25px;text-decoration:underline black'>${myMenuU1.value}  </span> yang suka <span style='font-weight:bolder;color:red'>${myMenuU2.value} </span>  nilai kamu <span style="font-family:monospace;text-shadow:0 0  12px black;color:gold;font-style:italic;font-size:25px;background-color:black">${nilai} </span> pada tingkat kesulitan <span style=' border: 2px solid black; color:white; background-color:green'>${tE} </span> <br>`)
      localStorage.setItem("data1",JSON.stringify(myData))
      textRank.innerHTML=JSON.parse(localStorage.getItem("data1"))
    }
    textRank.innerHTML=JSON.parse(localStorage.getItem("data1"))
    hapusData.onclick=()=>{
      localStorage.clear("data1")
      window.location.reload()
    }
    
    let indek=0
    let soal=["Hasil dari 6+6=","Hasil dari 5+3=","Hasil dari 3+3=","Hasil dari 7+2=","Hasil dari 4+6=","Hasil dari 5-4=","Hasil dari 7-5=","Hasil dari 11-6=","Hasil dari 12+12=","Hasil dari 33+33=","Hasil dari 50+25=","Hasil dari 20-5=","Hasil dari 20-7=" ,"Hasil dari 17-3=","Hasil dari 23+25=","Hasil dari 27+27=","Hasil dari 45+65=" ,"Hasil dari 6×6=" ,"Hasil dari 7×7=" ,"Hasil dari 5×5=" ,"Hasil dari 4×8=" ,"Hasil dari 100÷2=","Hasil dari 60÷2=","Hasil dari 400÷2=","Hasil dari 800÷2=","Hasil dari 125+25=","Hasil dari 175+50=","Hasil dari 500+50=","Hasil dari 400+15=","1000+5000-2000=","6000+6000-10000=","50000-25000=","7000+7000+10000=","Hasil dari 450+150","Hasil dari 750+220","Hasil dari 465+15=","Hasil dari 660+40=","Apakah 10>15? jawab Benar atau Salah","Apakah 25>23? jawab Benar atau Salah","Apakah 23<7? jawab Benar atau Salah"]
    function addSoal(){
        return question.innerHTML=soal[indek]
    }
    
    let naikLv=0
    function parameter(){
      if(inpt.value=="Salah"||inpt.value=="salah"){naikLv+=3456}
      else if(inpt.value=="Benar"||inpt.value=="benar"){naikLv+=3378}
      else if(inpt.value=="Salah"||inpt.value=="salah"){naikLv+=3243}
      else if(inpt.value==700){naikLv+=3146}
      else if(inpt.value==480){naikLv+=2985}
      else if(inpt.value==970){naikLv+=2879}
      else if(inpt.value==600){naikLv+=2754}
      else if(inpt.value==24000){naikLv+=2653}
      else if(inpt.value==25000){naikLv+=2589}
      else if(inpt.value==2000){naikLv+=2472}
      else if(inpt.value==4000){naikLv+=2345}
      else if(inpt.value==415){naikLv+=2276}
      else if(inpt.value==550){naikLv+=2139}
      else if(inpt.value==225){naikLv+=2045}
      else if(inpt.value==150){naikLv+=1976}
      else if(inpt.value==400){naikLv+=1894}
      else if(inpt.value==200){naikLv+=1776}
      else if(inpt.value==30){naikLv+=1623}
      else if(inpt.value==50){naikLv+=1529}
      else if(inpt.value==32){naikLv+=1418}
      else if(inpt.value==25){naikLv+=1362}
      else if(inpt.value==49){naikLv+=1245}
      else if(inpt.value==36){naikLv+=1123}
      else if(inpt.value==110){naikLv+=1019}
      else if(inpt.value==54){naikLv+=931}
      else if(inpt.value==48){naikLv+=832}
      else if(inpt.value==14){naikLv+=782}
      else if(inpt.value==13){naikLv+=673}
      else if(inpt.value==15){naikLv+=554}
      else if(inpt.value==75){naikLv+=473}
      else if(inpt.value==66){naikLv+=427}
      else if(inpt.value==24){naikLv+=397}
      else if(inpt.value==5){naikLv+=342}
      else if(inpt.value==2){naikLv+=298}
      else if(inpt.value==1){naikLv+=245}
      else if(inpt.value==10){naikLv+=175}
      else if(inpt.value==9){naikLv+=123}
      else if(inpt.value==6){naikLv+=54}
      else if(inpt.value==8){naikLv+=12}
      else if(inpt.value==12){naikLv++
    }else{naikLv+=1000}
    //prmtr.innerHTML=naikLv
    }
    
    displayGO.style.display="none"
    function displayGameOver(){
      setTimeout(()=>{
         inpt.style.backgroundColor="red"
      },200)
      setTimeout(()=>{
         question.style="text-decoration:10px line-through red;background-color:blue"
      },400)
      setTimeout(()=>{
        timer.style.color="red"
        myysoal.style.backgroundColor="tomato"
      },600)
      setTimeout(()=>{
        myynilai.style="text-decoration:8px line-through red"
      },800)
      setTimeout(()=>{
         inpt.style.display="none"
         display.style.display="none"
         question.style.display="none"
         timer.style.display="none"
         myysoal.style.display="none"
         myynilai.style.display="none"
      },1500)
      setTimeout(()=>{
         displayKalah()
      },1700)
    }
    
    function mulaiQuiz(tingkat){
      inpt.style.display="none"
      display.style.display="none"
      question.style.display="none"
      timer.style.display="none"
      myysoal.style.display="none"
      myynilai.style="background-color:white;border:none"
      tekan.style="width:220px;height150px;background-color:yellow;font-size:23px;color:black;border-radius:50px;border:2px solid black"
      tekan.innerHTML=` <span style="font-family:monospace;">waktu sudah berjalan pada tingkat kesulitan <span style=' border:2px solid black; background-color:aqua'>${tingkat} </span> silahkan tekan di sini </span>`
      
    }
    function kerjakanQuiz(){
      easy.style.display="none"
      medium.style.display="none"
      hard.style.display="none"
      myysoal.style.display=""
      myynilai.style=""
      inpt.style.display=""
      display.style.display=""
      question.style.display=""
      timer.style.display=""
      backMenuInti.style.display="none"
      tekan.style="width:95px;height150px;background-color:gray;font-size:25px;color:white;border-radius:50px;border:2px solid black"
      tekan.innerHTML="NEXT"
    }
    
    let nilai=0
    let tampGo=false
    function gameOverDanSkor(){
      switch(naikLv){
        case 1000:
          break
        case 1001:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 1013:
          nilai+=10
          break
        case 1067:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 1190:
          nilai+=10
          break
        case 1365:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 1610:
          nilai+=10
          break
        case 1908:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 2250:
          nilai+=10
          break
        case 2647:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 3074:
          nilai+=10
          break
        case 3547:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 4101:
          nilai+=10
          break
        case 4774:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 5556:
          nilai+=10
          break
        case 6388:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 7319:
          nilai+=10
          break
        case 8338:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 9461:
          nilai+=10
          break
        case 10706:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 12068:
          nilai+=10
          break
        case 13486:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 15015:
          nilai+=10
          break
        case 16638:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 18414:
          nilai+=10
          break
        case 20308:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 22284:
          nilai+=10
          break
        case 24329:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 26468:
          nilai+=10
          break
        case 28744:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 31089:
          nilai+=10
          break
        case 33561:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 36150:
          nilai+=10
          break
        case 38803:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 41557:
          nilai+=10
          break
        case 44436:
          nilai+=10
          tekan.style.backgroundColor="black"
          break
        case 47421:
          nilai+=10
          break
        case 50567:
          nilai+=10
          tekan.style.backgroundColor="black"
          inpt.type="text"
          break
        case 54023:
          nilai+=10
          break
        case 57401:
          nilai+=10
          tekan.style.backgroundColor="black"
          inpt.type="text"
          break
        case 60857:
          tamat.style.color="rgba(0,0,255,90%"
          tamat2.style.color="rgba(0,0,255,90%"
          tamat.innerHTML="Selamat Kamu Menang"
          tamat2.innerHTML="TAMAT"
          
      displayGameOver()
          break
        default:
        tampGo=true
        tekan.innerHTML="GAME OVER"
        displayGameOver()
      }
      skor.innerHTML=`<span style=' margin-left:13px;border:2px solid black; background-color:lime'>Nilai : </span> <span style=' border: 2px solid black; color:white; background-color:#222'></span>`
      if(nilai>0){
      setTimeout(()=>{
      skor.innerHTML=`<span style=' margin-left:13px;'>load</span>`},300)
      setTimeout(()=>{
      skor.innerHTML=`<span style=' margin-left:13px;'>loading</span>`},400)
      setTimeout(()=>{
      skor.innerHTML=`<span style=' margin-left:13px;'>loading..</span>`},500)
      setTimeout(()=>{
      skor.innerHTML=`<span style=' margin-left:13px;'>loading...</span>`},600)
      setTimeout(()=>{
      skor.innerHTML=`<span style=' margin-left:13px;'>loading....</span>`},700)
      setTimeout(()=>{
      skor.innerHTML=`<span style=' margin-left:13px;'>loading.....</span>`},800)
      setTimeout(()=>{
      skor.innerHTML=`<span style=' margin-left:13px;'>loading.....</span>`},900)
      
      setTimeout(()=>{
      skor.innerHTML=`<span style=' margin-left:13px;border:2px solid black; background-color:lime'>Nilai : </span> <span style=' border: 2px solid black; color:black; background-color:white'>${nilai} </span>`
      },1000)
      }
    }
    
    function waktuGame(seconds,tingkat){
      let waktu=setInterval(()=>{
        if(seconds>0){
          seconds--
          timer.innerHTML=`<span style=" margin-left:90px;background-color:blue;color:white;border:2px solid black;border-radius:12px">${tingkat}: ${seconds}`
        }else{
          clearInterval(waktu)
          displayGameOver()
          tekan.innerHTML="Waktu Habis"
        }
      },1000)
    }
    function tampSoal(){
      let dataSoal=[]
      dataSoal.push(soal[indek-1])
      let dataInpt=[]
      dataInpt.push(inpt.value)
      display.innerHTML=`<span style='  font-weight:bolder color:black; font-size:21px'> </span><br><br><span style="font-family:monospace;text-shadow:0 0  9px yellow;color:black;font-style:italic;font-size:21px;">${dataSoal} </span> <span style="font-size:21px">=></span><span style=' border:1px solid black; background-color:yellow;font-size:21px'>${dataInpt} </span><br>`
      if(nilai>0){
      setTimeout(()=>{
        display.innerHTML=`<span style='  color:black; font-size:21px'>●●●●●●●</span><br><br><span style="font-family:monospace;text-shadow:0 0  9px yellow;color:black;font-style:italic;font-size:21px;text-decoration:4px line-through black">${dataSoal} </span> <span style="font-size:21px">=></span><span style=' border:1px solid black; background-color:yellow;font-size:21px;text-decoration:4px line-through black'>${dataInpt} </span><br>`
      },400)
      setTimeout(()=>{
        display.innerHTML=`<span style='  color:black; font-size:21px'>●●●●●●●●</span><br><br><span style="font-family:monospace;text-shadow:0 0  9px yellow;color:black;font-style:italic;font-size:21px;text-decoration:4px line-through black">${dataSoal} </span> <span style="font-size:21px">=></span><span style=' border:1px solid black; background-color:yellow;font-size:21px;text-decoration:4px line-through black'>${dataInpt} </span><br>`
      },500)
      setTimeout(()=>{
        display.innerHTML=`<span style='  color:black; font-size:21px'>●●●●●●●●●</span><br><br><span style="font-family:monospace;text-shadow:0 0  9px yellow;color:black;font-style:italic;font-size:21px;text-decoration:4px line-through black">${dataSoal} </span> <span style="font-size:21px">=></span><span style=' border:1px solid black; background-color:yellow;font-size:21px;text-decoration:4px line-through black'>${dataInpt} </span><br>`
      },600)
      setTimeout(()=>{
        display.innerHTML=`<span style='  color:black; font-size:21px'>●●●●●●●●●●</span><br><br><span style="font-family:monospace;text-shadow:0 0  9px yellow;color:black;font-style:italic;font-size:21px;text-decoration:4px line-through black">${dataSoal} </span> <span style="font-size:21px">=></span><span style=' border:1px solid black; background-color:yellow;font-size:21px;text-decoration:4px line-through black'>${dataInpt} </span><br>`
      },700)
      setTimeout(()=>{
        display.innerHTML=`<span style='  color:black; font-size:21px'>●●●●●●●●●●●</span><br><br><span style="font-family:monospace;text-shadow:0 0  9px yellow;color:black;font-style:italic;font-size:21px;text-decoration:4px line-through black">${dataSoal} </span> <span style="font-size:21px">=></span><span style=' border:1px solid black; background-color:yellow;font-size:21px;text-decoration:4px line-through black'>${dataInpt} </span><br>`
      },800)
      setTimeout(()=>{
        display.innerHTML=`<span style='  color:black; font-size:21px'>●●●●●●●●●●●●</span><br><br><span style="font-family:monospace;text-shadow:0 0  9px yellow;color:black;font-style:italic;font-size:21px;text-decoration:4px line-through black">${dataSoal} </span> <span style="font-size:21px">=></span><span style=' border:1px solid black; background-color:yellow;font-size:21px;text-decoration:4px line-through black'>${dataInpt} </span><br>`
      },900)
      setTimeout(()=>{
        display.innerHTML=`<span style='  color:black; font-size:21px'></span><br><br><span style="font-family:monospace;color:black;font-variant:small-caps;font-size:26px;color:white;font-size:bolder;background-color:green">Jawabanmu Benar</span><br>`
      },1000)}
      if(tampGo){
      setTimeout(()=>{
        display.innerHTML=`<span style='  color:black; font-size:21px'></span><br><br><span style="font-family:monospace;color:black;font-variant:small-caps;font-size:40px;color:white;font-size:bolder;background-color:red">Jawabanmu salah</span><br>`
      },1000)} 
    }
    
    backMenuInti.style.display="none"
    mulaiMyMenuL.onclick=()=>{
      setTimeout(()=>{
        backMenuInti.style.display=""
        tingkatKesulitan.style.display=""
        intiGame.style.display="none"
      
        myMenuL.style.display="none"
      },500)
    }
    
    myMenuUClick.onclick=()=>{
    setTimeout(()=>{
      btn1.style.display=""
    },1000)
    setTimeout(()=>{
      btn2.style.display=""
    },1200)
    setTimeout(()=>{
      btn3.style.display=""
    },1400)
      let myName=myMenuU1.value
      let myHobby=myMenuU2.value
    setTimeout(()=>{
      myMenuU.style.display="none"
      myMenuL.style.display=""
    },500)
    }
    
  disRank.style.display="none"
  textRank.style.display="none"
  cekPeringkatMyMenuL.onclick=()=>{
    setTimeout(()=>{
      disRank.style.display=""
      textRank.style.display=""
      myMenuL.style.display="none"
    },500)
  }
  backMenu.onclick=()=>{
    setTimeout(()=>{
      myMenuL.style.display=""
      btn2.style.display=""
      btn3.style.display=""
      btn1.style.display=""
      disRank.style.display="none"
      textRank.style.display="none"
    },500)
  }
  backMenuInti.style.display="none"
  backMenuInti.onclick=()=>{
    setTimeout(()=>{
      myMenuL.style.display=""
      btn2.style.display=""
      btn3.style.display=""
      btn1.style.display=""
      backMenuInti.style.display="none"
      intiGame.style.display="none"
      tingkatKesulitan.style.display="none"
    },500)
  }
  
  let tE=""
  tingkatKesulitan.style.display="none"
  easy.onclick=()=>{
    if(true){tE="easy"}
    setTimeout(()=>{
      intiGame.style.display=""
      waktuGame(500,"Easy")
      mulaiQuiz("Easy")
      tingkatKesulitan.style.display="none"
    },500)
  }
  medium.onclick=()=>{
    if(true){tE="medium"}
    setTimeout(()=>{
      intiGame.style.display=""
      waktuGame(240,"Medium")
      mulaiQuiz("Medium")
      tingkatKesulitan.style.display="none"
    },500)
  }
  hard.onclick=()=>{
    if(true){tE="hard"}
    setTimeout(()=>{
      intiGame.style.display=""
      waktuGame(160,"hard")
      mulaiQuiz("Hard")
      tingkatKesulitan.style.display="none"
    },500)
  }
  function displayKalah(){
    displayGO.style.display=""
    textNG.innerHTML=`<span style="color:white;font-family:monospace"><span style=' border: 2px solid black; color:white; background-color:green'>${myMenuU1.value} </span>  nilai kamu <span style="font-family:monospace;text-shadow:0 0  9px yellow;color:white;font-style:italic;font-size:25px">${nilai} </span> pada tingkat kesulitan <span style=' border:2px solid black; background-color:yellow;color:black'>${tE} </span><br> Cek skor tertinggimu di menu <span style=' border:2px solid black; background-color:aqua;color:black'>cek nilai </span></span>`
  }
  btnRst.onclick=()=>{
    setTimeout(()=>{
      penyimpanan()
      window.location.reload()
    },500)
  }
  maker3.style.display="none"
  maker2.style.display="none"
  maker.style.display="none"
  tentangMyMenuL.onclick=()=>{
    setTimeout(()=>{
       myMenuL.style.display="none"
    setTimeout(()=>{
       maker3.style.display=""
    },800)
    setTimeout(()=>{
       maker2.style.display=""
    },700)
    setTimeout(()=>{
       maker.style.display=""
    },600)
    },500)
  }
  btnAbout.onclick=()=>{
    setTimeout(()=>{
       myMenuL.style.display=""
       maker.style.display="none"
    },500)
  }
    //silahkan di hias sesuai ke kereatifan kalian dan soalnya ditambah sebanyak banyaknya
  </script>
</body>
</html>
