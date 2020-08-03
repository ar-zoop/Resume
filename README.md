
<html>
    <head>
        <title>
            Arzoo's resume
        </title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

        <style>
            img{
                border:3px solid white;
                border-radius: 140px;
                width:250px;
                height:250px;
                float:left;
                margin-top:10px;
                display: block;
                margin-left: 10px;
                margin-right: auto;
                                
            }        

           

            hr{
                height:1px;
                background-color:rgb(96,132,77);
                border:none;
                margin-top:10px;
                /* rgb(192,218,141)' */
            }
            .edu-years{
                color:grey
            }
                
            .photo-spacing{               
                margin-bottom:25px
            }    

            .banner{
                text-align:center;
                background-color:rgb(96,132,77);
                color:white;
                padding: 5px

            }

        </style>
    </head>
    

    <body style='background-color: rgb(245,244,239);'>

        <script>
            function clear-field(){
                document.getElementById("email").value="";

            }

        </script>

        <div class="container" >
                
            <div class="row">
                
                <div class="col-md-10 col-md-offset-1 col-l-10 col-l-offset-1 col-xs-12 ;center-div"  >
                    <div class='banner' >
                        
                        <img src='arzoo.jpg' />                  
                        <h1 class='photo-spacing'>ARZOO BAPNA</h1>                    
                        <h3 class='photo-spacing'>Udaipur, Rajasthan</h3>
                        <h3 class='photo-spacing'>+91 1234567890</h3>
                        <h3 class='photo-spacing'>arzoobapna@gmail.com</h3>
                        
                    </div>

                    <br/>
                   

                    <div >
                        <center>
                            <h2>SUMMARY</h2>
                            <h4> | Learning CS since 2018. | Highschool graduate.| Pursuing B.Tech CS. |</h4>
                        </center>
                    </div>

                    <hr>

                    <div>
                        <center>
                            <h2>EDUCATION</h2>
                        </center>
                        <h4>                                
                            <ul>
                                <li>Techno India NJR Institute of Technology </li>
                                <h5>Bachelor of Technology-BTech, Computer Science</h5>
                                <h5 class='edu-years' >2020-2024</h5>

                                <li>St. Anthony's Sr. Sec. School</li>
                                <h5>11th and 12th class, PCM+CS</h5>
                                <h5 class='edu-years'>2016-2018 <br/>
                                    Activities and Societies: Music Band(violinist)

                                </h5>

                                <li>MDS Sr. Sec. School</li>
                                <h5>9th and 10th class studied in affiliation with <u>Resonance </u></h5>
                                <h5 class='edu-years'>2016-2018 <br/>
                                    Activities and Socities: First Batch Student, Basketball team, Music Band (violinist)

                                </h5>
                            </ul>                                
                        </h4>
                        
                    </div>

                    <hr>

                    <div>
                        <center>
                            <h2>SKILLS, TOOLS, CERTIFICATES</h2>
                        </center>
                        <h4>
                            <ul>
                                <h3>Skills</h3>
                                <li>Effective Communication</li>
                                <li>Public Speaking</li>
                                <h3>Tools</h3>
                                <li>Python</li>
                                <li>MySQL</li>
                                <li>HTML+css+Bootstrap</li>
                                <li>Javascript</li>
                                <h3>Certificates</h3>
                                <li><a href='https://www.coursera.org/account/accomplishments/certificate/FAY42GZ5V3JS'>Programming for Everybody (Getting Started with Python)</a></li>
                                <h5 class='edu-years'><Coursera <br/>
                                Issued Jun 2020. No Expiration Date 
                                </h5>
                            </ul>
                        </h4>

                    </div>

                    <hr>

                    <div class='well'>
                        <center>
                            <h2>CONTACT</h2>
                        </center>

                        <form>
                            <table border="0" style="margin: 0 auto; width:500px"> 
                                <tr>
                                    <td colspan='2'><h4><input type='text' placeholder='Your Name'></h4></td>
                                    <td colspan='2'><h4><input type='email' placeholder="Your email id"></h4></td>
                                </tr>
                                <tr>
                                    
                                    <td ><h4><input type='text' placeholder='Your Message'></h4></td>
                                   
                                </tr>
                                <tr>
                                    <td colspan='4'><h4><input type='submit' value='Send' id='email' onclick=clear-field()></h4></td>
                                </tr>
                            </table>
                        </form>
                    </div>



                </div>
            </div>
        </div>



    </body>


</html>
