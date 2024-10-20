<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Micro Project</title>
    <style>
        body
        {
            padding:0;
            margin:0;
        }
        nav
        {
            top:0;
            height:65px;
            width:100%;
            background-color: mediumpurple;
            padding:10px;
            display : flex;
            justify-content: space-between;
            align-items: center;
            box-sizing: border-box;
            position: fixed;
            
        }
        .children
        {

            
            height:40px;
            width:100px;
            display:flex;
           
            box-sizing: border-box;
            align-items: center;
            padding: 10px 5px;
            color:aliceblue;
            
            
            
        }
        .child1
        {
            font-size: 28px;
            font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }
        .child2
        {
            width:500px;
            display: flex;
            box-sizing: border-box;
           
            justify-content: space-between;
            align-items: center;
            
        }
        .child2>div
        {
            
            height:30px;
            width:100px;
            display: flex;
            box-sizing: border-box;
            padding: 4px;
            
            align-items: center;

            
        }
        input[type="text"]
        {
            width:100px;
            border-radius: 100px/500px;
        }
        .child3
        {
            width:40px;
        }
        main
        {
            height:340px;
            width: 96%;
            margin:120px 50px;
             /* Centering the container with margin */
            display: flex;
            margin-right:0;
            margin-bottom: 0;
            
            align-items: center;
            
            
            
            box-sizing: border-box;
        }
        main textarea
        {
            background-color:lavender;
            padding:10px;
            border-radius: 2.5%;
        }
        .social
        {
            height:185px;
            width:200px;
            
            margin-left: 20px;
            
            display: flex;
            flex-direction: column;
            text-align: center;
            
          
            
            
        }
        .social div
        {
            height:60px;
            width:70px;
            border: 2px solid black;
        }
        footer
        {
            margin:34px 50px;
            
            height:83px;
            width:1180px;
            box-sizing: border-box;
            display:flex;
            justify-content: space-between;
            
        }
        footer div
        {
            
            border-radius: 6%;
            height:83px;
            width:225px;

            
            font-size: 32px;
            box-sizing: border-box;
            line-height: 2;
            display:flex;
            
            padding: 4px 4px;;
            font-size: larger;
            color: aliceblue;
            font-family: 'Times New Roman', Times, serif;

        }
        footer div pre
        {
            margin:0;
            padding:0px 8px;
        }
        footer img
        {
            position: fixed;
            margin-left:1090px;
            margin-top:30px;
        }
        .body2
        {
            height:475px;
            width:1180px;
            margin:21px 49px;
            display: flex;
            
            padding:5px;
            box-sizing: border-box;
            background-color: blue;
        }
        .C1
        {
            display:flex;
            flex-direction: column;
            box-sizing: border-box;
            margin:32px 10px;
            
        }
        .C1 div
        {
            height:85px;
            width:285px;
            border:3.35px solid white;
            border-radius: 7%;
            color: white;
            padding: 20px;
            box-sizing: border-box;
            text-align: center;

            font-size: 20px;


        }
        .C2
        {
            margin:10px 15px;
            height:448px;
            width:825px;
            background-color: white;
            border-radius: 2.9%;
            padding:15px 25px;
            box-sizing: border-box;
        }
        .C2 div
        {
           
            margin:8px 12px;
            
            width:230px;
            display: flex;
            box-sizing: border-box;
            justify-content: space-between;
            
            font-family: 'Times New Roman', Times, serif;
            
        }
        .C2 button
        {
            margin:140px 665px;
            color: aliceblue;
            background-color: black;
            padding:10px 0px;
            width:120px;
            border-radius: 5%;
        }
        
        
       
        
    </style>
</head> 
<body>
    <nav>
    <!-- There are total of three children in the nav bar   -->
     <div class="children child1">
     <p  > Dappr </p>
     </div>
     <div class="children child2">
     <!-- child2 has 5 children -->
     <div style="width: 50px;"> <p> Home </p> </div>
     <div style="width: 70px;" > <p  > About us</p> </div>
     <div style="width: 85px;"> <p> Information </p></div>
     <div style="width: 45px;"> <p> More </p>   </div>
     <div><input type="text" name="search bar" placeholder="Search"> </div>    

     </div>
     <div class="children child3">
        <img style="  height: 30px; width:30px;   " src="./images/moreicon.png" alt="more icon">
     </div>



    </nav>

    <main>
        <div> <img style="border-radius: 5%;" height="340px" width="330px"  src="./images/code.jfif" alt="code img"> </div>
        <div style="margin-left: 50px;"><textarea name = "Code Editor" id="Editor" rows="20" cols="100" placeholder="Its not only writers who can benfit from this from this free online tool.If you are a programmer whos working on a........." ></textarea> </div>
        <div class="social" >   
            <!-- three children three images-->
             <div><img style="height: 60px; width:70px;"    src="./images/fbfull.jpg" alt="facebook" </div>
             <div> <img style="height: 60px; width:70px;" src="./images/wpfull.jpg" alt="whatsapp">       </div>
             <div style="margin-top: 2px;"> <img style="height: 60px; width:70px;" src="./images/twitterfull.jpg" alt="twitter" </div>
        </div>
    </main>
    <footer>
        <!--four children -->
        <div style="background-color: cornflowerblue;">
            <pre>Total Question's
200,000
            </pre>
        </div>
        <div style="background-color: rgb(137, 43, 226);">
            <pre>Total Answer's
105,000
                            </pre>
        </div>
        <div style="background-color: rgb(228, 17, 232);">
            <pre>Participated
10,000
                            </pre>
        </div>
        <img height="70" width="70"  src="./images/cropped-circle-bot.png" alt="Chatbot">
        <div style="background-color: black;">
            <pre>Total Passed
6,000
                            </pre>
        </div>
        
    </footer>

    <div class="body2"> 
        <!-- Two children -->
         <div class="C1">
            <!-- three children -->
             <div style="background-color: lightblue;color:black;border: none;"     class="C1 c1">
                YOUR INFO
             </div>
             <div class="C1 c2">
                BOOKMARKS
             </div>
             <div class="C1 c3">
                SETTINGS
             </div>
        </div>
         <div class="C2">
            <h1> Your Information</h1>
            <pre>  <b>Name</b>   :  Atul Singhal  </pre>
            <pre>  <b>Email</b>  :  atul@gmail.com</pre>
            <pre>  <b>Phone</b>  :  +91 8131424888</pre>
            <pre>  <b>Marks</b>  :  500.00</pre>
            <button > Next ---> </button>
            
        </div>
       


    </div>
    



</body>


</html>
