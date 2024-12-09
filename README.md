<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Domain</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/css/bootstrap.min.css" integrity="sha384-r4NyP46KrjDleawBgD5tp8Y7UzmLA05oM1iAEQ17CSuDqnUK2+k9luXQOfXJCJ4I" crossorigin="anonymous">
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/js/bootstrap.min.js" integrity="sha384-oesi62hOLfzrys4LxRF63OJCXdXDipiYWBnvTl9Y9/TRlw5xlKIEHpNyvvDShgf/" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.1/css/all.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="icon" href="./webImagesIcons/image.png" type="icon/image">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>
<body>
    <style>
        .id ul li{
            display: inline;
            color: gray;
        }
        .btn{
            background-color: rgb(17, 16, 16);
            color: gray;
           
        }
        .btn:hover{
            color:white;
        }
       li button{
        border:none;
        background-color:blue;
        color:white;
        border-radius:10px;
        margin: 2px 20px 2px 20px;
       }
       .liTop{
        margin: 10px;
        font-size: 18px;
    }
    
       li a{
        text-decoration-line: var(--line);
        color:gray;
        
    }
    .id ul .liBtn {
        margin-left:-10px;
    }
    .id ul .liLast {
        margin-left:8px;
        font-size: 18px;
    }
    li a:hover {
        color:white;
    }
    .p-4 ul li {
        list-style-type: var(--list);
    }
    :root {
        --list: none;
        --line: none;
    }
    .h5 {
        color:white;
    }
    li {
        margin-left:-30px;
    }
   .header-container:hover .id{
    cursor: pointer;
   }
   .liTop:hover {
    color:white;
   }
   .liList:hover {
    color:white;
   }
   button a:hover {
    color:white;
   }
  button a {
    text-decoration-line: none;
    color: white;
  }

.overlay {
    position: fixed; 
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.7); 
    display: none; 
    justify-content: center;
    align-items: center;
    z-index: 5000; 
  }
  
  .overlay-content {
    background-color: white;
    padding: 30px;
    border-radius: 8px;
    text-align: center;
    height:530px;
    width:390px;
    
  }
  .contentDropDown ul li{
    list-style-type: var(--list);
  }
  .trendsDropDown ul li {
    list-style-type: var(--list);
  }
 .solutionBtn ul li {
    list-style-type: var(--list);
 }
  .seoDropDown ul li{
    list-style-type: var(--list);
  } 
  .localDropDown ul li{
    list-style-type: var(--list);
  } 
  .advertisingDropDown ul li {
    list-style-type: var(--list);
  }
  .socialDropDown ul li {
    list-style-type: var(--list);
  }
  .management ul li{
    list-style-type: var(--list);
  }


  .main-container{position: relative; }
  .list { display: none; position: absolute;}
  .list .row .col-3 button{display: block;}
  .main-container:hover .list{display: block;}

    </style>

    
    <!--header-->
    <div class="header-container" style="width:100%;background-color: rgb(17, 16, 16);">
                <div class="container d-flex justify-content-between" style="position:relative;">
                        <div class="id" style="width:800px;">
                                <ul class="d-flex justify-content-between" style=" margin-bottom: 0px;">
                                    <li class="liTop ">Features</li>
                                    <li class="liTop ">Pricing</li>
                                    <li class="liBtn">
                                    <div class="main-container">
                                        <button class="btn dropdown-toggle">Resources</button>
                                        <div class="list mt-5 bg-dark text-white">
                                            <div class="row">
                                                <div class="col-3 p-4">
                                                    <p class="h3">Blog</p>
                                                    <p>Read the industry's latest thoughts on digital marketing, content strategy, SEO, PPC, social media and more.</p>
                                                </div>
                                                <div class="col-3 p-4">
                                                    <p class="h3">Help Center</p>
                                                    <p>Learn how to use Semrush with user manuals, how-to's, videos and more!</p>
                                                </div>
                                                <div class="col-3 p-4">
                                                    <p class="h3">What's New</p>
                                                    <p>Keep track of the newest Semrush features and improvements.</p>
                                                </div>
                                                <div class="col-3 p-4">
                                                    <p class="h3">Webinars</p>
                                                    <p>Register and take part in educational webinars conducted by the best digital marketing experts.</p>
                                                </div>
                                            </div>
                                            <div class="row">
                                                <div class="col-3 p-4">
                                                    <p class="h3">Insights</p>
                                                    <p>See the latest in original research and thought leadership from the Semrush team.</p>
                                                </div>
                                                <div class="col-3 p-4">  
                                                    <p class="h3">Hire a Trusted Agency</p>
                                                    <p>Pressed for time? Need rare skills? Get help from a trusted agency. Our experts work with marketing projects of all kinds and budgets.</p>
                                                </div>
                                                <div class="col-3 p-4">      
                                                    <p class="h3">Academy</p>
                                                    <p>Get vital SEO skills, learn how to use our toolkits and get official certificates of your proficiency in SEO and Semrush.</p>    
                                                </div>
                                                <div class="col-3 p-4">      
                                                    <p class="h3">Top Websites</p>
                                                    <p>Discover the most visited websites. Analyze their traffic and search rankings. Choose country or industry to find out who currently leads the market.</p>
                                                </div>
                                        </div>
                                        <div class="row">
                                                <div class="col-3 p-4">     
                                                    <P class="h3">Content Marketing Hub</P>
                                                    <p>Learn everything you need to know about effective content marketing in one place. Explore free tools, industry research, practical materials for your business, and more.</p>
                                                </div>
                                                <div class="col-3 p-4">  
                                                    <p class="h3">Local Marketing Hub</p>
                                                    <p class="">Start outperforming your nearby competition today! Discover the expert insights, strategies, and tools you need to increase the digital footprint of your business and get more local customers.</p>
                                                </div>
                                        </div>
                                    </div>
                                </div>
                                </li>
                                    <li><button class="btn dropdown-toggle">Company</button></li>
                                    <li><button class="btn dropdown-toggle ">App Center</button></li>
                                    <li class="liLast mt-2">Enterprise</li>
                                </ul>
                        </div>
                    <div>
                <button class="border border-2" style="font-size: 15px; width: 100px; position: absolute; left: 980px; height:34px; padding-left:10px;padding-right:10px;color:white;border-radius:5px;border:none;margin-top:2px;background-color: rgb(17, 15, 16);"><a href="./Login.html">Log In</a></button>
                <button class="ml-3" style="font-size: 15px; width: 100px; position: absolute; left: 1080px; padding-left:15px;padding-right:15px;padding-top:5px;padding-bottom:5px;color:white;border-radius:5px;border:none;margin-top:2px;background-color:gray"><a href="./Signup.html">Sign Up</a></button>
            </div>
        </div>
    </div>
    
    <!--main-container-left-->
    <style>
    </style>

    <div class="index-container d-flex" style="margin-top: 0px; margin-left: 0px;">

 <div class="main-container border border-5">
    <div class="side-container" style="width:100%">
<style>
</style>
        <div class="container seoDropDown">
           <div class="seoPosition">
           <!-- <i class="bi bi-arrow-up-right-circle" style=" color: white; font-size:x-large;position:absolute; left: 35px; top: 18px; z-index: 2000;"></i> --> 
            <button class="btnbtn " style="background-color:rgba(36, 138, 163, 0.349); color: black; position:relative;margin:10px;padding:10px;border:none;width:100%">SEO</button>
            </div>
                <div class="seoBtn">
                <h5 class="text-uppercase">Competitive research</h5>
            <ul>
                <li>Domain Overview
                    <li>Traffic Analytics </li>
                    <li>Organic Research </li>
                    <li>Keyword Gap </li>
                    <li>Backlink Gap </li>
            </ul>
            <h5 class="text-uppercase">keyword research</h5>
                <ul>
                    <li>Keyword Overview</li>
                    <li>Keyword Magic Tool</li>
                    <li>Keyword Strategy Builder</li>
                    <li>Position Tracking</li>
                    <li>Organic Traffic Insights</li>
                </ul>
            <h5 class="text-uppercase">link building</h5>
            <ul>
                <li>Backlink Analitics</li>
                <li>Backlink Audit</li>
                <li>Link Building Tool</li>
                <li>Bulk Analysis</li>
            </ul>
            <h5 class="text-uppercase">on page & tech seo</h5>
            <ul>
                <li>Site Audit</li>
                <li>Listing Management</li>
                <li>SEO Content Template</li>
                <li>On Pahe SEO Checker</li>
                <li>Log File Analyzer</li>
            </ul>
        </div>
<style>
   
</style>
        <div class="container localDropDown">
            <div class="localPosition">
                <i class="bi bi-geo-alt" style="color: white; font-size:x-large;position:absolute; left: 35px; top: 8px; z-index: 2000;"></i>
            <button class="btnbtn" style="background-color:rgba(36, 138, 163, 0.349); position:relative;margin:10px;padding:10px;border:none;color: black;width:100%">Local</button>
            </div>
            <div class="localBtn">
            <ul>
                    <li>Local Dashboard</li>
                </ul>
                <h5 class="text-uppercase" >toolkit</h5>
                <ul>
                    <li>GBP Optimization</li>
                    <li>Listing Management</li>
                    <li>Map Rank Tracker</li>
                    <li>Review Management</li>
                </ul>
                <h5 class="text-uppercase">seo tools essentials</h5>
                <ul>
                    <li>POsition Tracking</li>
                    <li>Site Audit</li>
                    <li>ON Page SEO Checker</li>
                </ul>
                </div>
        </div>
<style>
    
</style>
        <div class="container advertisingDropDown">
            <div class="advertisingPosition">
              <!-- <i class="bi bi-crosshair" style="font-size:x-large;position:absolute; left: 35px; top: 18px; z-index: 2000;"></i> --> 
                <button class="btnbtn " style="background-color:rgba(36, 138, 163, 0.349); position:relative;margin:10px;padding:10px;border:none;color:black;width:100%">Advertising</button>
            </div>
           <div class="advertisingBtn">     
           <ul> 
                <li>Advertising Dashboard</li>
            </ul>
                <h5 class="text-uppercase">market ananysis</h5>
                <ul>
                    <li>Domain Overview</li>
                    <li>Advertising Research</li>
                    <li>AdClarity</li>
                    <li>PLA Research</li>
                </ul>
                <h5 class="text-uppercase">keyword research</h5>
                <ul>
                    <li>Keyword Gap</li>
                    <li>Keyword Magic Tool</li>
                    <li>Keyword Strategy Builder</li>
                    <li>PPC Keyword Tool</li>
                    <li>Ads History</li>
                </ul>
                <h5 class="text-uppercase">ad management</h5>
                <ul>
                    <li>AdCreative.ai</li>
                    <li>Ads Launch Assistant <button style="margin-right: 100px; font-size: small">new</button></li>
                </ul>
                <h5 class="text-uppercase">ad tracking</h5>
                <ul>
                    <li>Position Tracking</li>
                </ul>
                </div>
        </div>
<style>
   
</style>
        <div class="container socialDropDown">
            <div class="socialPosition">
              <!--  <i class="bi bi-record-btn" style="font-size:x-large;position:absolute; left: 35px; top: 18px; z-index: 2000;"></i> --> 
           <button class="btnbtn " style="background-color:rgba(36, 138, 163, 0.349); position:relative;margin:10px;padding:10px;border:none;color:black;width:100%">Social Media</button>
            </div>
           <div class="socialBtn">     
           <h5 class="text-uppercase"></h5>
                <ul>
                    <li>Social Poster</li>
                    <li>Social Tracker</li>
                    <li>Social Content Insights <button style="margin-right: 100px; font-size: small">beta</button></li>
                    <li>Social Analytics</li>
                    <li>Social Content AI <button style="margin-right: 100px; font-size: small">new</button></li>
                    <li>Influencer Analytics</li>
                </ul>
                </div>
        </div>
<style>
    
</style>
        <div class="container contentDropDown">
            <div class="contentPosition">
            <button class="btnbtn " style="background-color:rgba(36, 138, 163, 0.349); position:relative;margin:10px;padding:10px;border:none;color:black;width:100%">Content Marketing</button>
            </div>
            <div class="contentBtn">
            <h5 class="text-uppercase">Get Started</h5>
                <ul>
                    <li>Topic Research</li>
                    <li>SEO Content Template</li>
                    <li>SEO Writing Assistant</li>
                    <li>Brand Monitoring</li>
                    <li>ContentShake AI <button style="margin-right: 100px; font-size: small">new</button></li>
                </ul>
                </div>
        </div>
<style>
   
</style>
        <div class="container trendsDropDown">
            <div class="trendsPosition">
             <!--   <i class="fa-solid fa-chart-column" style="font-size:x-large;position:absolute; left: 35px; top: 18px; z-index: 2000;"></i> --> 
            <button class="btnbtn " style="background-color:rgba(36, 138, 163, 0.349); position:relative;margin:10px;padding:10px;border:none;color: black;width:100%">.Trends</button>
            </div>
            <div class="trendsBtn">
            <h5 class="text-uppercase">Get Started</h5>
                <ul>
                    <li>Traffic Analytics</li>
                    <li>Market Explorer</li>
                    <li>EyeOn</li>
                    <li>One2Target</li>
                </ul>
                </div>
        </div>
<style>
    
</style>
        <div class="container solutionDropDown">
            <div class="solutionPosition">

           <button class="btnbtn" style="background-color:rgba(36, 138, 163, 0.349); position:relative;margin:10px;padding:10px;border:none;color:black;width:100%">Agency Solutions</button>
        </div>
           <div class="solutionBtn">     
           <h5 class="text-uppercase">lead generation</h5>
                <ul>
                    <li>Agency Partners</li>
                    <li>Lead Finder</li>
                </ul>
                <h5 class="text-uppercase">optimization & automation</h5>
                <ul>
                    <li>Client POrtal</li>
                    <li>CRM</li>
                    <li>My Reports</li>
                </ul>
                </div>
        </div>
    </div>
    <div class="container management">
        <h5 class="text-uppercase">management</h5>
        <ul>
            <li>My Reports</li>
            <li>Notes</li>
        </ul>
    </div>
    <div class="container p-1">
        <ul>
            <li class="p-1">Online demo</li>
            <li class="p-1">SEOquake for your browser</li>
            <li class="p-1">Hire a digital agency</li>
            <li class="p-1">Join our Affiliate</li>
            <li class="p-1">Have you seen our new customizable API format?</li>
            <li class="p-1">Sensor</li>
            <li class="p-1">Prowly</li>
            <li class="p-1">Semrush Rank</li>
            <li class="p-1">Winners & Losers</li>
        </ul>
    </div>
 </div>
</div>


<!--main-container-right-->
<style>
 
 .anchor{ }
</style>

    <div class="main-container" style="background-color: rgb(233, 237, 238); width: 100%;">

    <div class="container mt-4 m-5 p-5 bg-white" style="border-radius: 10px;width:1018px">
        <div class="row">
            <h1 style="text-align:center;">Domain Overview</h1>
            <h5 style="padding:20px">Get instant insights into strengths and weaknesses of your competitor or prospective customer.</h5>
        </div>
        <div class="row" style="padding:10px">
            <div class="col-5"><input placeholder=" Enter domain, subdomain, or URL" class="border border-1" type="text" style="height:50px;width:450px;border-radius:5px;border:none" ></div>
            <div class="col-3 offset-1"><input class="border border-1" type="text" style="height:50px;width:100%;border-radius:5px;border:none"></div>
            <div class="col-3 "><input type="button" value="Search" style="width:100px;color:white;background-color:gray;border-radius:10px;border:none;padding:15px"></div>
        </div>
        <div class="row" style="padding:5px">
            <p>Examples:&nbsp;&nbsp;&nbsp;<a href="https://www.worldwildlife.org/" target="_blank" >worldwildlife.org</a>&nbsp;&nbsp;<a href="https://www.unicef.org/stories" target="_blank" >unicef.org/stories</a>&nbsp;&nbsp;<a href="#https://edition.cnn.com/" target="_blank" >edition.cnn.com</a>&nbsp;&nbsp;&nbsp;Already registered?&nbsp;
                <button class="btnColor" style = "border: none; background-color: white;" onclick="showOverlay()"><a href="#" style="color: blue;"class="anchor">Log in</a></button></p>
        </div>
    </div>
        <div class="container bg-white" style="border-radius: 10px;width:1018px;margin-top:20px; margin-bottom: 20px;">
            <div class="row bg-white"">
                <div class="d-flex">
                <div class="col-5 mt-3">
                     <img src="./webImages/Web-Design-and-Web-Development-Companies.png" alt="" width="300px" height="300px" class="m-5" style="border-radius: 10px;">
                 </div>
                 <div class="col-6 mt-5">
                    <h3 class="p-1" style="margin-left:-23px">Get a complete analysis</h3>
                    <ul class="">
                        <li class="p-1" style="margin-right:200px">Get a full overview of a domain and its online visibility</li>
                        <li class="p-1">Analyze a domain's growth trend over time</li>
                        <li class="p-1" style="margin-right:250px">See the markets where a domain has the leading representation</li>
                        <li class="p-1" style="margin-right:170px">Discover the top keywords that bring the most traffic from the organic and paid channels</li>
                    </ul>
                 </div>
                </div>
        </div>
        <div class="row d-flex bg-white">
            <div class="col-6 mt-5">
                <h3 class="p-1" style="margin-left:75px">Compare Domains</h3>                
                <ul class="">
                        <li class="p-1" style="margin-left:70px">Save time spent on summary analysis. Compare up to five competitors within one report</li>
                        <li class="p-1" style="margin-left:70px">Uncover and analyze the key metrics either for a specific country or globally: organic search traffic, paid search traffic, and number of backlinks</li>
                        <li class="p-1" style="margin-left:70px">Choose domain type: root domain, subdomain, subfolder</li>
                </ul>
            </div>
            <div class="col-5">
                <img src="./webImages/pictures.jfif" alt="" width="300px" height="300px" class="m-5 bg-white" style="border-radius: 10px;">
            </div>
        </div>
        <div class="row d-flex bg-white">
            <div class="col-5">
                <img src="./webImages/images.jfif" alt="" width="300px" height="300px" class="m-5" style="border-radius: 10px;">
            </div>
            <div class="col-7 mt-5">
                <h3 class="p-1" style="margin-left:-25px">Growth Report</h3>
                <ul>
                        <li class="p-1" style="margin-right:200px">Save time on reporting by getting the key data on a domain's growth trend in one place</li>
                        <li class="p-1" style="margin-right:200px">Evaluate a domain's progress for organic traffic, paid traffic, and backlinks for a specific period: three months, a quarter, 6 months, a season, or 1 year</li>
                        <li class="p-1" style="margin-right:200px">Easily export the report to xls or csv</li>
                </ul>
            </div>
        </div>
        <div class="row d-flex">
            <div class="col-6 mt-1 mb-5">
                <h3 class="p-1" style="margin-left:75px">Compare by Countries</h3>         
                <ul class="">
                    <li class="p-1" style="margin-left:70px">Compare organic and paid performance of a domain in different countries</li>
                    <li class="p-1" style="margin-left:70px">See the organic share of a domain for specific markets</li>
                    <li class="p-1" style="margin-left:70px">Export the trends to xls or csv</li>
                </ul> 
            </div>
            <div class="col-5 mb-5">
                <img src="./webImages/Get-the-Most-Fancied-Web-Development-Services-min-scaled.jpg" alt="" width="300px" height="300px" class="" style="border-radius: 10px;">
            </div>
        </div>
        </div>
        <div class="container m-5 p-5 m-5 p-5 bg-white" style="width: 100%;border-radius: 10px;width:1018px;margin-top:20px; margin-bottom: 100px;">
            <div class="row">
                <div class="col-12">
                     <h3 class="p-5 ml-3">Get 7-day unlimited access to all Semrush tools and reports</h3>
                     <button class="mb-5" style="margin-left:300px;width:150px;padding:13px;background-color:gray;border:none;color:white;border-radius:5px;">Get free trail</button>
                     <button class="ml-2" onclick="showOverlay()" style="padding:13px;background-color:rgb(189, 186, 186);border:none;color:white;border-radius:5px;">Log in</button>
                </div>
        </div>
    </div>
</div>

<script>

function showOverlay() {
    const overlay = document.getElementById('overlay');
    overlay.style.display = 'flex';
  }
  
  function hideOverlay() {
    const overlay = document.getElementById('overlay');
    overlay.style.display = 'none'; 
  }

</script>

</div>

<!--footer-->
<div class="footer" style="width: 100%;">
    <div class="container-fluid">
        <div class="row p-4" style="background-color:rgb(24, 21, 24)">
            <div class="col-12 d-flex mt-3" >
            <div class="col-2"><button class="btn btn-dark border border-2 px-5" type="button">Contact Us</button></div>
            <div class="ml-3"><p style="color:gray">USA, 800 Boylston Street, Suite 2475, Boston, MA 02199</p></div>
            <div class="col-3" style="margin-left:200px">
                <button class="text-white"style="background-color:rgb(173, 173, 173);width:390px;border:none;border-radius:5px;padding-top:10px;padding-bottom:10px"><a href="./loignWith.html">Get started with semrush!</a></button>
                <div class="row mt-2">
                    <a href="#"><p>or see our plans & pricing</p></a>
                </div>
            </div>
        </div>
        </div>
        <div class="row p-4" style="background-color:rgb(24, 21, 24)">
            <div class="col-2">
                <div class="row">
                    <div class="col-3">
                <p class="h5">Semrush</p>
                <ul>
                    <li><a href="http://" target="_blank" rel="noopener noreferrer">Features</a></li>
                    <li><a href="http://" target="_blank" rel="noopener noreferrer">Pricing</a></li>
                    <li><a href="http://" target="_blank" rel="noopener noreferrer">Success Stories</a></li>
                    <li><a href="http://" target="_blank" rel="noopener noreferrer">Stats and Facts</a></li>
                    <li><a href="http://" target="_blank" rel="noopener noreferrer">Insights</a></li>
                    <li><a href="http://" target="_blank" rel="noopener noreferrer">News</a></li>
                </ul>
            </div>
        </div>
        <div class="col-3">
           <p class="h5">Help</p>
           <ul>
                    <li><a href="http://" target="_blank" rel="noopener noreferrer">Knowledge Base</a></li>
                    <li><a href="http://" target="_blank" rel="noopener noreferrer">Academy</a></li>
                    <li><a href="http://" target="_blank" rel="noopener noreferrer">Semrush API</a></li>
            </ul>
        </div>
        </div>
            <div class="col-2">
               <p class="h5">Community</p> 
               <ul>
                    <li><a href="http://" target="_blank" rel="noopener noreferrer">Semrush Blog</a></li>
                    <li><a href="http://" target="_blank" rel="noopener noreferrer">Webinars</a></li>
                </ul>
            </div>
            <div class="col-2">
                <p class="h5">More tools</p>
                <ul>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Analytics Reports</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Projects</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Agency Partners</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Affiliate Program</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">SEOquake</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Sensor</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Prowly</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Kompyte</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">SplitSignal</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Ryte</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">App Center</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Enterprise SEO</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Free Tools</a></li>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Free AI Writing Tools</a></li>
                    </ul>
            </div>
            <div class="col-2">
               <p class="h5">Company</p> 
               <ul>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">About Us</a>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Newsroom</a>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Careers</a>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Partners</a>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Legal Info</a>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Privacy Policy</a>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer"> Cookie Settings</a>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Do not sell my personal info</a>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Security Info</a>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">For Investors</a>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Semrush Select</a>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Global Issues Index</a>
                        <li><a href="http://" target="_blank" rel="noopener noreferrer">Contact Us</a>
                     </ul>
            </div>
            <div class="col-2">
               <p class="h5">Follow us</p> 
               <ul>
                        <li><a href="https://x.com/?lang=en-in" target="_blank" rel="noopener noreferrer">X (Twitter)</a>
                        <li><a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer">Facebook</a>
                        <li><a href="https://in.linkedin.com/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
                        <li><a href="https://www.instagram.com/" target="_blank" rel="noopener noreferrer">Instagram</a>
                        <li><a href="https://www.youtube.com/?gl=IN" target="_blank" rel="noopener noreferrer">YouTube</a>
                        <li><a href="https://www.pinterest.com/" target="_blank" rel="noopener noreferrer">Pinterest</a>
                    </ul>
            </div>
            <div class="col-2 drpdown">
                    <p class="h5">Language</p>
                    <div class="drop" style="width:100px;height:200px">
                        <select name="" id="">
                        <option class="opt" style="padding:3px;background-color:rgb(24,21,24);color:white">English</option>
                        <option style="padding:3px;background-color:rgb(24,21,24);color:white">Deutsch</option>
                        <option style="padding:3px;background-color:rgb(24,21,24);color:white">Espanol</option>
                        <option style="padding:3px;background-color:rgb(24,21,24);color:white">Francais</option>
                        <option style="padding:3px;background-color:rgb(24,21,24);color:white">Italiano</option>
                        <option style="padding:3px;background-color:rgb(24,21,24);color:white">Nederlands</option>
                        <option style="padding:3px;background-color:rgb(24,21,24);color:white">Polski</option>
                        <option style="padding:3px;background-color:rgb(24,21,24);color:white">Portugues</option>
                        <option style="padding:3px;background-color:rgb(24,21,24);color:white">Svenska</option>
                        <option style="padding:3px;background-color:rgb(24,21,24);color:white">Denmark</option>
                    </select>
                </div>
            </div><style>.opt:focus{background-color:lightblue;}</style>
        </div>
        <div class="row">

        </div>
        <div class="row p-4" style="background-color:rgb(22, 7, 7);color:gray">
            <div class="col-5 offset-3">
                © 2008 - 2024 Semrush. All rights reserved.
            </div>
        </div>
    </div>
</div>


<!--overlay -->
<style>
    .overlay i:hover{color:black;}
</style>
<div id="overlay" class="overlay">
    <div class="overlay-content">
      <button onclick="hideOverlay()" class= "btn" style="background-color: white; font-size: larger; border: none; margin-left: 280px;"><i class="bi bi-x-lg"></i></button>
      <p class="h3 w-25" style="margin-left: 3px;">Log in</p>
      <form action="./loginPHP.php" class="">
          <div class="col-12 mt-3">
            <div class="row d-block">
                    <div class="col-8" >
                        <div class="row mr-2">
                            <label for="email" class="m-2 w-25" style="font-size:20px; ">Email</label></div>
                            <input type="text" class="border border-1 email" id="email" style=" border: none; border-radius: 5px; height: 40px; width: 300px;">
                        </div>
                    <div class="col-8">
                        <div class="row mr-2">
                            <label for="password"style="font-size:20px;">Enter your password</label></div>
                            <input type="text" class="password border border-1" id="password" style=" border: none; border-radius: 5px; height: 40px; width: 300px;">
                        </div>
            </div>
        </div>
        <div class="col-8 offset-5 mt-3">
              <a href="#">Forgot your password</a>
        </div>
        <div class="col-12" style="margin-top: 40px; border-radius: 5px; font-size:20px;">
              <button class=" w-100 h-100 border border-1" style="font-size: 20px; border: none; border-radius: 10px; background-color: chartreuse;">Log in</button>
        </div>
        <div class="row mt-2">
          <p style="font-size:20px;">Don't have semrush account&nbsp;<a href="./signUpoverlay.html" style="text-decoration: none; font-size:20px;">Sign up</a></p>
        </div>
    </form>
    </div>
  </div>


  
</body>
</html>



