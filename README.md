# mdrief-iastate.github.io
<!DOCTYPE HTML>
<html>
<head>
    <title>Matt Rief</title>
    <meta charset="utf-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1"/>
    <link rel="stylesheet" href="style/style.css"/>
    <!-- CSS only -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css"
          integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">

</head>
<body class="main" style="background-color: rgb(28,28,28); overflow-x: hidden">
<section class="hero">
    <nav class="navbar navbar-expand-lg">
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a id="link1" class="nav-link text-light abel" href="#about">About <span
                            class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item active">
                    <a id="link2" class="nav-link text-light abel" href="#experience">Experience <span
                            class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item active">
                    <a id="link3" class="nav-link text-light abel" href="#projects">Projects <span class="sr-only">(current)</span></a>
                </li>
            </ul>
            <a id="link4" href="files/resume.pdf" download>
                <button class="btn btn-outline-light" type="submit">Resume</button>
            </a>
        </div>
    </nav>

    <h1 class="big-blue-text main-text">Matt Rief</h1>
    <div style="text-align: center">
        <p class="secondary-text"
           style="display: inline-block; width: 50%; text-align: left; font-size: 20px; color: #ffffff;">
            I am a Senior at Iowa State University majoring in Electrical Engnineering.
        </p>
    </div>
    <div class="center" style="margin-top: 27vh">
        <a href="https://github.com/mdrief-iastate"><img class="hover" src="images/github-large.png"
                                                         style="height: 120px; width: 120px; margin: 1vw;"></a>
        <a href="https://www.linkedin.com/in/matthew-r-30905816b/"><img class="hover"
                                                                              src="images/linkedin.png"
                                                                              style="height: 107px; width: 107px;"></a>
        <a href="photos.html"><img class="hover"
                                                                              src="images/icons8-camera-250.png"
                                                                              style="height: 120px; width: 120px; margin: 1vw;"></a>
    </div>
</section>

<!-- Experience -->
<section id="experience" style="display: flex; align-items: center">
    <div style="margin: 0 10vh 0 10vh; vertical-align: middle">
        <div class="card-deck">

            <div class="card w-75 project-card border-0">
                <img class="card-img-top" src="images/netapp/netapp_logo_1.jpg" style="background-color: #ffffff"
                     alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">NetApp - Software Engineer Intern</h5>
                    <p class="card-text">
                        Systems Engineering Intern <strong>(May 22' - Present)</strong> - Worked as a Systems Engineer on the BAE Systems miniturized gps receiver team in Cedar Rapids.
                    </p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">
                        <ul class="experience-list">
                            <li>
                                Coming soon.
                            </li>
                        </ul>
                    </small>
                </div>
            </div>

            <div class="card w-75 project-card border-0">
                <img class="card-img-top" src="images/moo/moo.svg" style="background-color: #ffffff"
                     alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Scripps Institute of Oceanagraphy - Engineering Aide</h5>
                    <p class="card-text">
                        Site Reliability Engineering Intern <strong>(Aug 20' - May 21')</strong> -
                        Worked as a full-stack developer on Mutual of Omaha's Site Reliability team.</p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">
                        <ul class="experience-list">
                            <li>Constructed functional tests for a serverless AWS service to ensure that the
                                functionality of the application remains in-tact throughout new builds.
                            </li>
                            <li>
                                Migrated an application from the CloudFormation template to the AWS Cloud Development Kit.
                            </li>
                            <li>
                                Created AWS dashboards to display Amazon Connect WebRTC metric data.
                            </li>
                        </ul>
                    </small>
                </div>
            </div>

            <div class="card w-75 project-card border-0">
                <img class="card-img-top" src="images/moo/moo.svg" style="background-color: #ffffff"
                     alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Mutual of Omaha - Application Developer Intern</h5>
                    <p class="card-text">
                        Application Developer Intern <strong>(Jun 20' - Aug 20')</strong> -
                        Worked as a full-stack developer on Mutual of Omaha's in house applications that support our
                        marketing team. </p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">
                        <ul class="experience-list">
                            <li>Maintained and supported various microservices by writing unit tests, debugging
                                code, and
                                fixing runtime errors.
                            </li>
                            <li>Constructed software that automates excel reports to drastically lower report
                                preparation time.
                            </li>
                            <li>Upgraded a microservice from IBM Web Sphere to Apache Tomcat, then transitioned that
                                web-service into a Spring Boot application from Java Servlets to reduce technical
                                debt.
                            </li>
                        </ul>
                    </small>
                </div>
            </div>

            <div class="card w-75 project-card border-0">
                <img class="card-img-top" src="images/moo/moo.svg" style="background-color: #ffffff"
                     alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Mutual of Omaha - Application Developer Intern</h5>
                    <p class="card-text">
                        Application Developer Intern <strong>(May 19' - Aug 19')</strong> -
                        Worked as a full-stack developer on Mutual of Omaha's in house applications that support our
                        marketing team. </p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">
                        <ul class="experience-list">
                            <li>Developed a Gradle plugin that is to be used inside of a Jenkins pipeline to
                                send
                                files
                                from Jenkins
                                to another server where they can be properly requested using Solr.
                            </li>
                            <li>Created a REST service using Spring that allowed my team to view the health of
                                our
                                microservices.
                            </li>
                            <li>Upgraded a microservice???s frontend from Angular 2 to Angular 8 to reduce
                                technical
                                debt.
                            </li>
                        </ul>
                    </small>
                </div>
            </div>
        </div>

    </div>
</section>

<!-- Projects -->
<section id="projects" style="padding: 3vh 5vh 15vh;">
    <div style="">
        <div class="card-deck">
            <div class="card w-75 project-card border-0">
                <img class="card-img-top" src="images/projects/vision.png" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Vision</h5>
                    <p class="card-text">Vision is a home automation system. Think of it as a cheap alexa clone with
                        many
                        less features. Originally it was built in Python, but it is currently in a Kotlin
                        re-write. </p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">Utilized: Kotlin, JavaScript, React.JS, Spring Boot, Gradle,
                        Travis-CI,
                        SonarCloud
                        <a style="float: right;" href="https://github.com/JackGoldsworth/Vision2"><img
                                src="images/github.png"></a>
                    </small>
                </div>
            </div>


            <div class="card project-card border-0">
                <img class="card-img-top" src="images/projects/trex.png" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">DumbCode</h5>
                    <p class="card-text">DumbCode is a Minecraft modding team that develops some of the most
                        advanced
                        Minecraft mods to date. Our flagship mod is called Project Nublar, which adds dinosaurs to
                        Minecraft.</p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">Utilized: Java, JavaScript, Gradle, Travis-CI, SonarCloud, Gradle API,
                        OpenGL
                        <a style="float: right;" href="https://github.com/Dumb-Code"><img
                                src="images/github.png"></a>
                    </small>
                </div>
            </div>

            <div class="card project-card border-0">
                <img class="card-img-top" src="images/projects/hwk.png" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">HwK</h5>
                    <p class="card-text">HwK is an imperative programming language that runs on the JVM. The
                        language
                        compiles down to java byte code with
                        the help of the ASM library. The grammar was created and parsed using ANTLR. </p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">Utilized: Java, Kotlin, ASM, ANTLR4, Gradle, Travis-CI, SonarCloud
                        <a style="float: right;" href="https://github.com/JackGoldsworth/HwK2"><img
                                src="images/github.png"></a>
                    </small>
                </div>
            </div>
        </div>

        <!-- ROW 2 -->
        <div class="card-deck" style="margin-top: 2vh">
            <div class="card project-card border-0">
                <img class="card-img-top" src="images/projects/serviceroomba.png" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Service Roomba</h5>
                    <p class="card-text">Service Roomba is a piece of embedded software developed to run on
                        a modified Roomba, that will allow that Roomba to autonomously traverse an obstacle
                        course.</p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">Utilized: C, UART, PuTTY, IR Sensor, Servo motor, ADC
                        <a style="float: right;" href="https://github.com/JackGoldsworth/Service-Roomba"><img
                                src="images/github.png"></a>
                    </small>
                </div>
            </div>


            <div class="card project-card border-0">
                <img class="card-img-top" style="object-fit: scale-down" src="images/projects/jurassicraft.png"
                     alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">JurassiCraft</h5>
                    <p class="card-text">JurassiCraft is a Minecraft mod based off of Jurassic Park, and it adds
                        dinosaurs to Minecraft. It has been downloaded over 6 Million times and has a very active
                        community. </p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">Utilized: Java, Gradle, Gradle API, OpenGL, MCForge
                        <a style="float: right;"
                           href="https://www.curseforge.com/minecraft/mc-mods/jurassicraft"><img
                                style="max-width: 32px; max-height: 32px;" src="images/website.png"></a>
                    </small>
                </div>
            </div>

            <div class="card project-card border-0">
                <img class="card-img-top" src="images/projects/selectunes.png" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">SelecTunes</h5>
                    <p class="card-text">SelecTunes is an android app that allows you host song parties,
                        and it allows the listeners to vote for the next song!</p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">Utilized: Kotlin, Spotify-API, Android-API, Mockito, Volley, Gradle,
                        Gitlab
                        CI/CD
                        <a style="float: right;" href="https://github.com/SelecTunes"><img src="images/github.png"></a>
                    </small>
                </div>
            </div>
        </div>
        <div class="text-center">
            <a href="https://github.com/JackGoldsworth">
                <button class="btn  btn-outline-light" style="margin-top: 3vh;" type="submit">More Projects</button>
            </a>
        </div>
    </div>
</section>
</body>
</html>
