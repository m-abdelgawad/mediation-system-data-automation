<a name="readme-top"></a>

[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="imgs/logo.png" alt="Logo" width="80" height="80">
  <h3 align="center">Mediation System Data Automation</h3>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#business-case">Business Case</a></li>
        <li><a href="#technical-solution">Technical Solution</a></li>
        <li><a href="#screenshots">Screenshots</a></li>
        <li><a href="#tech-stack">Tech Stack</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

* **Project Name:** Mediation System Data Automation
* **Version:** v1.0.0  
* **Department:** Technology

---

### Business Case

The Mediation system requires the analysis of logs from a Solaris server and data from multiple Oracle database tables to provide full visibility into system performance. Previously, I had to manually log into the Solaris system to find and download six different logs, run separate database queries, and merge the results. This was a lengthy, frustrating, and error-prone process.

This tool automates the entire process, reducing a multi-hour task to just two clicks and less than two minutes, pulling logs, running database queries, and merging the data into a final report that provides critical insights into the system.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Technical Solution

The solution automates the acquisition and analysis of both Solaris log files and Oracle database records, merging them into one comprehensive dataset. Key features include:

* **Log File Retrieval:** Automatically pulls the latest six logs from the Solaris remote server, across different paths, based on file name patterns.
* **Database Queries:** Runs seven queries on six different Oracle database tables and retrieves essential data.
* **Data Cleaning:** Cleans the raw, often "dirty" data to ensure accuracy.
* **CPU & Memory Analysis:** Analyzes system performance, including CPU and memory utilization.
* **Feature Engineering:** Builds two dataframes with full information about the system.
* **Data Export:** Saves both raw and cleaned datasets in `.csv` files for further analysis or storage.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Screenshots

<img src="imgs/1.PNG">
<img src="imgs/2.PNG">
<img src="imgs/3.PNG">
<img src="imgs/4.PNG">
<img src="imgs/5.PNG">
<img src="imgs/6.PNG">
<img src="imgs/7.PNG">
<img src="imgs/8.PNG">
<img src="imgs/9.PNG">
<img src="imgs/10.PNG">
<img src="imgs/11.PNG">
<img src="imgs/12.PNG">
<img src="imgs/13.PNG">
<img src="imgs/14.PNG">
<img src="imgs/15.PNG">
<img src="imgs/16.PNG">

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Tech Stack

This project was developed using the following technologies:

* **Python** (Libraries: `pandas`, `numpy`, `matplotlib`, `sqlalchemy`, `paramiko`, `time`, `datetime`, `sys`)
* **VS Code** (Text Editor)
* **Git** (Version Control)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Mohamed AbdelGawad Ibrahim - [@m-abdelgawad](https://www.linkedin.com/in/m-abdelgawad/) - <a href="tel:+201069052620">+201069052620</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/m-abdelgawad/
