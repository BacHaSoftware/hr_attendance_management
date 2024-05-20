
<a name="readme-top"></a>

<!-- PROJECT DETAILS -->
<br />
<div align="center">
  <a href="https://github.com/BacHaSoftware/hr_attendance_management">
    <img src="/bhs_hr_attendance/static/description/icon.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">HR Attendance Management</h3>

  <p align="center">
    A product of Bac Ha Software allows to check in with location, multi workingtime, tracking late minutes, restrict attendance with IP.
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <!-- <li><a href="#prerequisites">Prerequisites</a></li> -->
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact-us">Contact us</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<div align="left">
  <a href="https://github.com/BacHaSoftware/hr_attendance_management">
    <img src="/bhs_hr_attendance/static/description/banner.gif" alt="Setting">
  </a>
</div>

#### Key Features:

🌟 <code>Check In Location</code>: Allow employees to check in at many locations (home, company, other). You can config these locations to suit your organization.

<div align="left">
    <a href="https://github.com/BacHaSoftware/hr_attendance_management">
        <img src="/bhs_hr_attendance/static/description/imgs/screen/loc.png" alt="Setting">
    </a>
</div>

🌟 <code>Restrict Attendance</code>: Configuring whitelist IP, device of users must in this IP to be able to check in at company. Record device, browser, IP, location when check in.

<div align="left">
    <a href="https://github.com/BacHaSoftware/hr_attendance_management">
        <img src="/bhs_hr_attendance/static/description/imgs/screen/ip.png" alt="Setting">
    </a>
</div>

🌟 <code>Auto Check Out</code>: Automatically check out at the end of working day. You can configure check out time to suit your organization.

<div align="left">
    <a href="https://github.com/BacHaSoftware/hr_attendance_management">
        <img src="/bhs_hr_attendance/static/description/imgs/screen/cron.png" alt="Setting">
    </a>
</div>

🌟 <code>Late Minutes By Working Schedules</code>:Allow employees to choose working schedule, record late minutes and automatically checkout according to this working schedule.

<div align="left">
    <a href="https://github.com/BacHaSoftware/hr_attendance_management">
        <img src="/bhs_hr_attendance/static/description/imgs/screen/time.png" alt="Setting">
    </a>
</div>

🌟 <code>Notify Late Minutes</code>: Notify when check in if employees is late for work and what time they have to work until. Late minutes is computed according to the working schedule above.

<div align="left">
    <a href="https://github.com/BacHaSoftware/hr_attendance_management">
        <img src="/bhs_hr_attendance/static/description/imgs/screen/late.png" alt="Setting">
    </a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

<!-- PREREQUISTES  
### Prerequisites

This module needs the Python library <code>slackclient</code>, <code>html-slacker</code>, otherwise it cannot be installed and used. Install them through the command
  ```sh
  sudo pip3 install slackclient
  sudo pip3 install html-slacker
  ```
 -->
### Installation

1. Install module <code>bhs_hr_attendance</code>
2. Config working hours detail and set working hour for each employee.
3. Config white list IP for employee attendance.
4. Config attendance locations.
5. Config user attendance requirements correctly in User information by check <code>Restrict Attendance</code> checkbox
6. Config cron auto checkout

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Module allows to check in with location, multi workingtime, tracking late minutes, restrict attendance with IP.


#### Featured Highlight:

🌟 <code>Simple Setup</code>: Configure directly in settings: whitelist IP, working schedules. There are 3 attendance locations after installed module: home, company, other, you can edit them at menu attendance location config.

🌟 <code>Comprehensive Attendance Management</code>: Provide comprehensive solutions to problem related to employees attendance management.


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT US-->
## Contact us
Need assistance with setup or have any concerns? Contact Bac Ha Software directly for prompt and dedicated support:
<div align="left">
  <a href="https://github.com/BacHaSoftware">
    <img src="/bhs_hr_attendance/static/description/imgs/logo.png" alt="Logo" height="80">
  </a>
</div>

📨 odoo@bachasoftware.com

🌍 [https://bachasoftware.com](https://bachasoftware.com)

[![WEBSITE][website-shield]][website-url] [![LinkedIn][linkedin-shield]][linkedin-url]

Project Link: [https://github.com/BacHaSoftware/hr_attendance_management](https://github.com/BacHaSoftware/hr_attendance_management)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-url]: https://github.com/BacHaSoftware/hr_attendance_management/blob/17.0/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/company/bac-ha-software
[website-shield]: https://img.shields.io/badge/-website-black.svg?style=for-the-badge&logo=website&colorB=555
[website-url]: https://bachasoftware.com