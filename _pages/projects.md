---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<div style="box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2); transition: 0.3s; width: 100%; margin-bottom: 20px;"  onmouseover="this.style.boxShadow='0 8px 16px 0 rgba(0,0,0,0.2)';" onmouseout="this.style.boxShadow='0 4px 8px 0 rgba(0,0,0,0.2)';">
    <div style="padding: 10px 20px;">
        <div style="padding: 4px 0; display: flex; justify-content: space-between; align-items: center;">
            <div>
                <img src="/images/project5.png" 
                     alt="usc logo" style="height: 60px; width:60px; padding:5px; border-radius: 20%; background-size: cover; vertical-align:middle;"/>
                 <b><a href="https://web-sh-hw8.uc.r.appspot.com/search" style="text-decoration: none;  color:#0096FF; font-size:20px;" onmouseover="this.style.color = '#0096FF'; this.style.textDecoration = 'underline #89CFF0';" onmouseout="this.style.color = '#0096FF'; this.style.textDecoration = 'none';">Ticketmaster Booking Application</a></b>
            </div>
        </div>
        <br>
        <span><b>Technologies: </b> AngularJS, NodeJS, Typescript, GCP</span>
        <br>
        <ul style="text-align: justify;">
            <li>Created a TicketMaster booking application using AngularJS for the frontend and NodeJS for the backend.</li>
            <li>The app allows users to search for events using different filters, with the backend retrieving filtered results from the TicketMaster API. </li>
            <li>It includes features like autocomplete and sorting for results, and users can add events to their favorites.</li>
            <li>Additionally, a NodeJS API is implemented to fetch artists' data in parallel, ensuring low latency within the application.</li>
        </ul>
    </div>
</div>
<br>

<div style="box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2); transition: 0.3s; width: 100%; margin-bottom: 20px;"  onmouseover="this.style.boxShadow='0 8px 16px 0 rgba(0,0,0,0.2)';" onmouseout="this.style.boxShadow='0 4px 8px 0 rgba(0,0,0,0.2)';">
    <div style="padding: 10px 20px;">
        <div style="padding: 4px 0; display: flex; justify-content: space-between; align-items: center;">
            <div>
                <img src="/images/project1.png" 
                     alt="usc logo" style="height: 60px; width:60px; padding:5px; border-radius: 20%; background-size: cover; vertical-align:middle;"/>
                <b style="font-size:20px;">API Documentation Tool</b>
            </div>
        </div>
        <br>
        <span><b>Technologies: </b> React, Python, Swagger, SQLite, GitLab</span>
        <br>
        <ul style="text-align: justify;">
            <li>Improved the process of creating and managing API documentation by creating an internal centralized tool using Swagger Editor, Swagger UI, and Open API Specifications.</li>
            <li>This initiative effectively addressed redundancy, incomplete documentation, and difficulty locating specific documents..</li>
        </ul>
    </div>
</div>
<br>

<div style="box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2); transition: 0.3s; width: 100%; margin-bottom: 20px;"  onmouseover="this.style.boxShadow='0 8px 16px 0 rgba(0,0,0,0.2)';" onmouseout="this.style.boxShadow='0 4px 8px 0 rgba(0,0,0,0.2)';">
    <div style="padding: 10px 20px;">
        <div style="padding: 4px 0; display: flex; justify-content: space-between; align-items: center;">
            <div>
                <img src="/images/project3.png" 
                     alt="usc logo" style="height: 60px; width:60px; padding:5px; border-radius: 20%; background-size: cover; vertical-align:middle;"/>
                <b style="font-size:20px;">Enhancement of Image Upload Architecture and Infrastructure</b>
            </div>
        </div>
        <br>
        <span><b>Technologies: </b> Go, RabbitMQ, Redis, Docker, Containers, AWS, DynamoDB, Postgres</span>
        <br>
        <ul style="text-align: justify;">
            <li>Revamped the architecture and infrastructure of the image upload service, previously taking around 400ms to complete.</li>
            <li>Utilizing Golang for parallel processing, RabbitMQ for background metadata handling, DynamoDB for temporary metadata storage, and AWS for cloud-based image storage, user experience saw substantial enhancements.</li>
            <li>This optimized strategy enhanced user experience during image uploads, ensuring a seamless journey within milliseconds, thereby reducing image service time from <b>400ms to 40ms</b>.</li>
        </ul>
    </div>
</div>
<br>

<div style="box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2); transition: 0.3s; width: 100%; margin-bottom: 20px;"  onmouseover="this.style.boxShadow='0 8px 16px 0 rgba(0,0,0,0.2)';" onmouseout="this.style.boxShadow='0 4px 8px 0 rgba(0,0,0,0.2)';">
    <div style="padding: 10px 20px;">
        <div style="padding: 4px 0; display: flex; justify-content: space-between; align-items: center;">
            <div>
                <img src="/images/project4.png" 
                     alt="usc logo" style="height: 60px; width:60px; padding:5px; border-radius: 20%; background-size: cover; vertical-align:middle;"/>
                <b style="font-size:20px;">Procedure for Synchronizing User Information in Go</b>
            </div>
        </div>
        <br>
        <span><b>Technologies: </b> Go, RabbitMQ, Docker, Containers, MySQL, Postgres, Cassandra</span>
        <br>
        <ul style="text-align: justify;">
            <li>The project aimed to identify and rectify unsynchronized user data across fifteen databases daily.</li>
            <li>This involved implementing a scheduled cron job to identify user IDs updated within the last 24 hours. </li>
            <li>Using a Golang procedure, I executed fifteen parallel goroutines to synchronize data into the respective databases based on these IDs.</li>
            <li>This solution effectively mitigated the problem of data unsynchronization.</li>
        </ul>
    </div>
</div>
<br>

<div style="box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2); transition: 0.3s; width: 100%; margin-bottom: 20px;"  onmouseover="this.style.boxShadow='0 8px 16px 0 rgba(0,0,0,0.2)';" onmouseout="this.style.boxShadow='0 4px 8px 0 rgba(0,0,0,0.2)';">
    <div style="padding: 10px 20px;">
        <div style="padding: 4px 0; display: flex; justify-content: space-between; align-items: center;">
            <div>
                <img src="/images/project2.png" 
                     alt="usc logo" style="height: 60px; width:60px; padding:5px; border-radius: 20%; background-size: cover; vertical-align:middle;"/>
                <b style="font-size:20px;">Automated GST Tax Collection, Matching, and Allocation</b>
            </div>
        </div>
        <br>
        <span><b>Technologies: </b> PHP, Go, RabbitMQ, MYSQL, Postgres</span>
        <br>
        <ul style="text-align: justify;">
            <li>To validate the GST information of potential paid sellers on Indiamart, we developed a method to enhance user authenticity.</li>
            <li>It involved extracting GSTs from both a third-party API and MasterIndia API, utilizing parallel processes to identify the best-matched GST for users, and allocating verified GSTs to users.</li>
            <li>This initiative resulted in a notable <b>20%</b> surge in paid sellers.</li>
        </ul>
    </div>
</div>
<br>