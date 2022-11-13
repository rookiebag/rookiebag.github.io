<html>
<head>
    <title>Vishal Suri</title>
    <!-- FONTS -->
    <link href='https://fonts.googleapis.com/css?family=Open+Sans:300,400,600' rel='stylesheet' type='text/css'>
    <link href='https://fonts.googleapis.com/css?family=Raleway:100' rel='stylesheet' type='text/css'>
    <link href='https://fonts.googleapis.com/css?family=Montserrat' rel='stylesheet' type='text/css'>
    <style>
        * {
            box-sizing: border-box;
            transition: 0.35s ease;
        }
        .rela-block {
            display: block;
            position: relative;
            margin: auto;
            top: ;
            left: ;
            right: ;
            bottom: ;
        }
        .rela-inline {
            display: inline-block;
            position: relative;
            margin: auto;
            top: ;
            left: ;
            right: ;
            bottom: ;
        }
        .floated {
            display: inline-block;
            position: relative;
            margin: false;
            top: ;
            left: ;
            right: ;
            bottom: ;
            float: left;
        }
        .abs-center {
            display: false;
            position: absolute;
            margin: false;
            top: 50%;
            left: 50%;
            right: false;
            bottom: false;
            transform: translate(-50%, -50%);
            text-align: center;
            width: 88%;
        }
        body {
            font-family: 'Open Sans';
            font-size: 18px;
            letter-spacing: 0px;
            font-weight: 400;
            line-height: 28px;
            background: url("http://kingofwallpapers.com/leaves/leaves-016.jpg") right no-repeat;
            background-size: cover;
            background-color: #000000
        }
        body:before {
            content: "";
            display: false;
            position: fixed;
            margin: 0;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(255,255,255,0.92);
        }
        .caps {
        text-transform: uppercase;
        }
        .justified {
        text-align: justify;
        }
        p.light {
        color: #777;
        }
        h2 {
        font-family: 'Open Sans';
        font-size: 30px;
        letter-spacing: 5px;
        font-weight: 600;
        line-height: 40px;
        color: #000;
        }
        h3 {
        font-family: 'Open Sans';
        font-size: 21px;
        letter-spacing: 1px;
        font-weight: 600;
        line-height: 28px;
        color: #000;
        }
        .page {
        width: 90%;
        max-width: 1200px;
        margin: -16px auto;
        background-color: #fff;
        box-shadow: 6px 10px 28px 0px rgba(0,0,0,0.4);
        }
        .top-bar {
        height: 220px;
        background-color: #848484;
        color: #fff;
        }
        .name {
        display: false;
        position: absolute;
        margin: false;
        top: false;
        left: calc(350px + 5%);
        right: 0;
        bottom: 0;
        height: 120px;
        text-align: center;
        font-family: 'Raleway';
        font-size: 58px;
        letter-spacing: 8px;
        font-weight: 100;
        line-height: 60px;
        }
        .name div {
        width: 94%;
        }
        .side-bar {
        display: false;
        position: absolute;
        margin: false;
        top: 60px;
        left: 5%;
        right: false;
        bottom: 0;
        width: 350px;
        background-color: #f7e0c1;
        padding: 320px 30px 50px;
        }
        .mugshot {
        display: false;
        position: absolute;
        margin: false;
        top: 50px;
        left: 70px;
        right: false;
        bottom: false;
        height: 210px;
        width: 210px;
        }
        .mugshot .logo {
        margin: -23px;
        }
        .logo {
        display: false;
        position: absolute;
        margin: false;
        top: 0;
        left: 0;
        right: false;
        bottom: false;
        z-index: 100;
        margin: 0;
        color: #000;
        height: 250px;
        width: 250px;
        }
        .logo .logo-svg {
        height: 100%;
        width: 100%;
        stroke: #000;
        cursor: pointer;
        }
        .logo .logo-text {
        display: false;
        position: absolute;
        margin: false;
        top: 58%;
        left: ;
        right: 16%;
        bottom: ;
        cursor: pointer;
        font-family: "Montserrat";
        font-size: 55px;
        letter-spacing: 0px;
        font-weight: 400;
        line-height: 58.333333333333336px;
        }
        .social {
        padding-left: 60px;
        margin-bottom: 20px;
        cursor: pointer;
        }
        .social:before {
        content: "";
        display: false;
        position: absolute;
        margin: false;
        top: -4px;
        left: 10px;
        right: false;
        bottom: false;
        height: 35px;
        width: 35px;
        background-size: cover !important;
        }
        .social.twitter:before {
        background: url("https://cdn3.iconfinder.com/data/icons/social-media-2026/60/Socialmedia_icons_Twitter-07-128.png") center no-repeat;
        }
        .social.pinterest:before {
        background: url("https://cdn3.iconfinder.com/data/icons/social-media-2026/60/Socialmedia_icons_Pinterest-23-128.png") center no-repeat;
        }
        .social.linked-in:before {
        background: url("https://cdn3.iconfinder.com/data/icons/social-media-2026/60/Socialmedia_icons_LinkedIn-128.png") center no-repeat;
        }
        .side-header {
        font-family: 'Open Sans';
        font-size: 18px;
        letter-spacing: 4px;
        font-weight: 600;
        line-height: 28px;
        margin: 60px auto 10px;
        padding-bottom: 5px;
        border-bottom: 1px solid #888;
        }
        .list-thing {
        padding-left: 25px;
        margin-bottom: 10px;
        }
        .content-container {
        margin-right: 0;
        width: calc(95% - 350px);
        padding: 25px 40px 50px;
        }
        .content-container > * {
        margin: 0 auto 25px;
        }
        .content-container > h3 {
        margin: 0 auto 5px;
        }
        .content-container > p.long-margin {
        margin: 0 auto 50px;
        }
        .title {
        width: 80%;
        text-align: center;
        }
        .separator {
        width: 240px;
        height: 2px;
        background-color: #999;
        }
        .greyed {
        background-color: #ddd;
        width: 100%;
        max-width: 580px;
        text-align: center;
        font-family: 'Open Sans';
        font-size: 18px;
        letter-spacing: 6px;
        font-weight: 600;
        line-height: 28px;
        }
        @media screen and (max-width: 1150px) {
        .name {
            color: #fff;
            font-family: 'Raleway';
            font-size: 38px;
            letter-spacing: 6px;
            font-weight: 100;
            line-height: 48px;
        }
        }
        li {
            line-height:1px;
        }
    </style>
</head>
<body>
<!-- PAGE STUFF -->
<div class="rela-block page">
    <div class="rela-block top-bar">
        <div class="caps name"><div class="abs-center">Vishal Suri</div></div>
    </div>
    <div class="side-bar">
        <div class="mugshot">
            <div class="logo">
                <svg viewbox="0 0 80 80" class="rela-block logo-svg">
                    <path d="M 10 10 L 52 10 L 72 30 L 72 70 L 30 70 L 10 50 Z" stroke-width="2.5" fill="none"/>
                </svg>
                <p class="logo-text">VS</p>
            </div>
        </div>
        <p>71 ClayLane</p>
        <p>Oldbury, Langley Green, B694TH</p>
        <p>07415777383</p>
        <p>vishalsuri001@gmail.com</p><br>
        <p class="rela-block social linked-in"><a href="www.linkedin.com/in/vishal-suri-001">Vishal Suri</a></p>
        <p class="rela-block caps side-header">Career Summary</p>
        <p class="rela-block">Started career as software executive from a finance organization, coding passion leads me to a programmer with 7+ years’ experience, now focused on becoming a Full Stack developer.</p>
        <p class="rela-block caps side-header">Journey</p>
        <p class="rela-block list-thing"><a href="http://oakfurnitureland.co.uk/">
            Oak Furniture Land (Swindon, UK)</a>
            <ul>
                <li>Sr. PHP Programmer</li>
                <li>Jun 2022 – Present</li>
            </ul>
        </p>
        <p class="rela-block list-thing"><a href="https://www.shiptrix.in">TrixAim Services (Ludhiana, India)</a>
            <ul>
                <li>Sr. PHP Programmer</li>
                <li>Apr 2021 – Apr 2022</li>
            </ul>
        </p>
        <p class="rela-block list-thing"><a href="https://www.netsolutions.com">NetSolutions (Chandigarh, India)</a>
            <ul>
                <li>PHP Programmer</li>
                <li>Sep 2018 – Mar 2021</li>
            </ul>
        </p>
        <p class="rela-block list-thing"><a href="https://www.multichannelcreative.co.uk">MultiChannelCreative (India, UK)</a>
            <ul>
                <li>PHP Programmer</li>
                <li>Feb 2015 – May 2018</li>
            </ul>
        </p>
        <p class="rela-block list-thing"><a href="https://techiesindiainc.com">Techies India Inc (Ludhiana, India)
        </a>
            <ul>
                <li>PHP Programmer</li>
                <li>Jan 2014 – Jan 2015</li>
            </ul>
        </p>
        <p class="rela-block list-thing"><a href="https://jaguarsoftwareindia.com">Jaguar Software (Jalandhar, India)
        </a>
            <ul>
                <li>Software Executive</li>
                <li>Aug 2012 – Oct 2013</li>
            </ul>
        </p>
        <p class="rela-block caps side-header">Education</p>
        <p class="rela-block list-thing">M.SC (IT) - Punjab Technical Uni. (2012)</p>
        <p class="rela-block list-thing">B.SC (Sci) - Guru Nanak Dev Uni. (2009)</p>
        <p class="rela-block caps side-header">Skill Highlights</p>
        <p class="rela-block list-thing">PHP, MySQL, LAMP, WAMP</p>
        <p class="rela-block list-thing">Codeigniter, Laravel, Custom-Framework</p>
        <p class="rela-block list-thing">jQuery, Javascript</p>
        <p class="rela-block list-thing">GIT, SVN</p>
        <p class="rela-block list-thing">API Integration and development</p>
        <p class="rela-block list-thing">OOP, web development, MVC</p>
        <p class="rela-block list-thing">React (In-progress)</p>
        <p class="rela-block caps side-header">Languages</p>
        <p class="rela-block list-thing">English, Hindi, Punjabi</p>
    </div>
    <div class="rela-block content-container">
        <h2 class="rela-block caps title">Sr PHP Developer</h2>
        <div class="rela-block separator"></div>
        <div class="rela-block caps greyed">Profile</div>
        <p class="long-margin">Senior Web Developer, with relentless work ethic, looking for challenging and rewarding opportunities to build and deliver diverse skills to achieve cooperate goals. Comfortable collaborating with front-end developers, project managers and designers. Have capabilities to adopt new technologies, trends and environment.</p>
        <div class="rela-block caps greyed">Project History</div>

        <h3>OakFurniture – Oak Furniture Land</h3>
        <p class="light">Sr. PHP Developer</p>
        <p class="justified">Work on a custom framework, fix runtime issues, build admin functionalities</p>
        
        <h3>Shiptrix.in – TrixAim, Ludhiana, India</h3>
        <p class="light">Sr. Web Developer</p>
        <p class="justified">Shiptrix is a shipping solution and a SAAS application built from scratch, to ship their own parcel with their own selected courier company.</p>
        <p class="justified">
            Responsibilities
            • Cooperate with designers to create clean interfaces and simple, intuitive interactions and experiences.
            • Develop project concepts, design and maintain optimal workflow.
            • Complete detailed programming and development tasks for front
            end public and internal websites as well as challenging back-end
            server code.
            • Carry out quality assurance tests to discover errors and optimize
            usability
        </p>
        
        <h3>EuroCarParts – NetSolutions, Chandigarh, India</h3>
        <p class="light">PHP Developer</p>
        <p class="justified">ECP is ecommerce platform to buy car parts as per vehicle registration number or Model details. ECP is providing services in UK, France, Ireland.</p>
        <p class="justified">
            Responsibilities
            • Assist in project maintenance
            • Built site features
            • Impact analysis before deployment
        </p>

        <h3>BodyguardWorkWear – MCC, Goraya, India</h3>
        <p class="light">PHP Developer</p>
        <p class="justified">Bodyguardworkwear is ecommerce and SAAS platform built from scratch, providing its services in UK.</p>
        <p class="justified">
            Responsibilities 
            • Built and design application from scratch.
            • Built key features such as product attribute system
            • Completed the tasks in provided time frame
            • Developed and Integrate APIs.
            • Configurable features as per client profile.
        </p>

        <h3>CheekyDevil – Techies India, Ludhiana, India</h3>
        <p class="light">PHP Developer</p>
        <p class="justified">CheekyDevil is a dating site and person can search for partner as per their choice from registered user.</p>
        <p class="justified">
            Responsibilities 
            • Boost the website performance
            • Optimize SQL
        </p>
    </div>
</div>
</body>
</html>