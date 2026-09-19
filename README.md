Yes — **now I understand exactly what you mean**. You don't want the previous badge-heavy README design.

You want the README to **visually follow the portfolio shown in your images**:

* dark futuristic background
* large **HARIKA JETTI** on the left
* **ServiceNow Developer → Full Stack Developer → Cloud Computing Enthusiast** animated underneath
* small **OPEN TO WORK** indicator
* location line
* left-side navigation style: **ABOUT / EXPERIENCE / PROJECTS / EDUCATION / SKILLS / GITHUB**
* content displayed on the right
* glowing lavender/purple accents instead of the green shown in the reference
* minimal, premium, futuristic appearance
* animated particles/glow
* your actual ServiceNow projects, certifications, internships and skills
* **everything in one single README**, so you can copy the entire block and paste it directly into `README.md`

One important difference: GitHub README files cannot create a truly fixed sidebar or JavaScript particle background like a website can. The README below recreates the **same visual concept using GitHub-supported HTML, animated SVGs and tables**.

````markdown
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0B0812&text=&fontColor=FFFFFF&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Montserrat&weight=800&size=52&duration=1&pause=100000&color=B79BEF&center=true&vCenter=true&width=900&height=80&lines=HARIKA+JETTI" />

<br>

<img src="https://readme-typing-svg.demolab.com?font=Montserrat&weight=600&size=23&duration=2200&pause=900&color=9B7EDE&center=true&vCenter=true&width=900&height=50&lines=ServiceNow+Developer;Full+Stack+Developer;Cloud+Computing+Enthusiast&repeat=true" />

<br>

<img src="https://readme-typing-svg.demolab.com?font=Montserrat&weight=500&size=13&duration=2800&pause=900&color=C8BEDB&center=true&vCenter=true&width=750&height=35&lines=Automating+workflows+%E2%80%A2+Building+applications+%E2%80%A2+Exploring+cloud;Turning+ideas+into+working+solutions+%E2%80%A2+Always+learning&repeat=true" />

<br>

<img src="https://img.shields.io/badge/%E2%97%8F%20OPEN%20TO%20WORK-9B7EDE?style=flat-square&labelColor=17121F&color=9B7EDE"/>

<br><br>

📍 **Visakhapatnam, Andhra Pradesh, India**

</div>

<br>

---

<table>
<tr>
<td width="24%" valign="top">

<br>

### <font color="#9B7EDE">━━━━━━━━</font>

### <font color="#9B7EDE">ABOUT</font>

<br>

`01`

<br>

### <font color="#B79BEF">EXPERIENCE</font>

<br>

`02`

<br>

### <font color="#B79BEF">PROJECTS</font>

<br>

`03`

<br>

### <font color="#B79BEF">EDUCATION</font>

<br>

`04`

<br>

### <font color="#B79BEF">SKILLS</font>

<br>

`05`

<br>

### <font color="#B79BEF">GITHUB</font>

<br>

`06`

<br><br>

</td>

<td width="76%" valign="top">

# <font color="#B79BEF">ABOUT</font>

<font color="#9B7EDE">━━━━━━━━</font>

### Hi, I'm Harika Jetti 👋

I am a **B.Tech Computer Science & Engineering student at NSRIT (Autonomous), Visakhapatnam**, interested in building practical technology solutions, automating workflows and continuously expanding my development skills.

My primary area of focus is **ServiceNow Development**, with hands-on experience in:

- ITSM
- Service Catalog
- Flow Designer
- Application Development
- Workflow Automation
- Business Rules
- Client Scripts
- UI Policies
- ACLs
- Update Sets
- Scoped Applications

Alongside ServiceNow, I am developing my skills in **Python, Full Stack Development, SQL, PostgreSQL and Cloud Computing**.

My goal is to keep building real-world solutions that combine **automation, application development and cloud technologies**.

</td>
</tr>
</table>

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Montserrat&weight=700&size=18&duration=2600&pause=900&color=9B7EDE&center=true&vCenter=true&width=700&height=40&lines=BUILDING+%E2%80%A2+AUTOMATING+%E2%80%A2+LEARNING+%E2%80%A2+GROWING" />

</div>

---

<table>
<tr>
<td width="24%" valign="top">

### <font color="#9B7EDE">EXPERIENCE</font>

`02`

<br><br>

**EduSkills**

<br>

Python Full Stack Development

<br><br>

**APSSDC**

<br>

Cloud Computing

</td>

<td width="76%" valign="top">

# <font color="#B79BEF">EXPERIENCE</font>

<font color="#9B7EDE">━━━━━━━━</font>

## Python Full Stack Development Intern

### EduSkills

Gained practical exposure to **Python and Full Stack Development** through internship-based learning and hands-on development.

<br>

## Cloud Computing Intern

### APSSDC

Gained practical exposure to **Cloud Computing concepts and cloud-based technologies**.

</td>
</tr>
</table>

---

<table>
<tr>
<td width="24%" valign="top">

### <font color="#9B7EDE">PROJECTS</font>

`03`

<br><br>

⚡

<br>

**Automated Network Request Management**

<br><br>

👥

<br>

**Employee Onboarding**

</td>

<td width="76%" valign="top">

# <font color="#B79BEF">PROJECTS</font>

<font color="#9B7EDE">━━━━━━━━</font>

## ⚡ Automated Network Request Management in ServiceNow

> A ServiceNow-based solution for automating the end-to-end lifecycle of network-related service requests.

### Core System

```text
SERVICE CATALOG
       │
       ▼
NETWORK REQUEST
       │
       ▼
DYNAMIC FORM
       │
       ▼
FLOW DESIGNER
       │
       ▼
CREATE RECORD
       │
       ▼
APPROVAL
       │
   ┌───┴───┐
   ▼       ▼
APPROVED  REJECTED
   │       │
   ▼       ▼
UPDATE    UPDATE
RECORD    RECORD
   │
   ▼
EMAIL NOTIFICATION
````

### Features

| Area               | Implementation            |
| ------------------ | ------------------------- |
| Request Submission | Service Catalog           |
| Dynamic Forms      | UI Policies               |
| Automation         | Flow Designer             |
| Data               | Custom Table              |
| Approvals          | Automated Approval Flow   |
| Notifications      | Email Notifications       |
| Security           | ACLs                      |
| Validation         | Catalog / Form Validation |
| Tracking           | Request Lifecycle         |

### ServiceNow Components

```text
Service Catalog
      │
      ├── Network Request
      │
      ▼
Dynamic Forms
      │
      └── UI Policies
      │
      ▼
Custom Table
      │
      ▼
Flow Designer
      │
      ├── Get Catalog Variables
      ├── Create Record
      ├── Ask for Approval
      ├── Send Email
      └── Update Record
      │
      ▼
Access Control
      │
      └── ACLs
```

### Dynamic Request Logic

```text
Connection Type
      │
      ├───────────────┐
      │               │
     NEW           EXISTING
      │               │
      ▼               ▼
Existing ID       Existing ID
Hidden            Displayed
```

### Project Demo

<p align="left">
<a href="https://drive.google.com/file/d/1WjS0AEqxdho9KFJY0qqG3X2gI9L0dVYY/view?usp=sharing">
<img src="https://img.shields.io/badge/VIEW%20PROJECT%20DEMO-9B7EDE?style=for-the-badge&logo=google-drive&logoColor=white"/>
</a>
</p>

<br>

## 👥 Employee Onboarding

A ServiceNow-based employee onboarding solution involving:

```text
Service Catalog
      ↓
Request Submission
      ↓
Approval Process
      ↓
Task Management
      ↓
Notifications
      ↓
Employee Information
      ↓
Request Tracking
```

### Key Areas

* Service Catalog integration
* Workflow automation
* Approval process
* Task management
* Notifications
* Employee information management
* Request tracking

</td>
</tr>
</table>

---

<table>
<tr>
<td width="24%" valign="top">

### <font color="#9B7EDE">EDUCATION</font>

`04`

<br><br>

🎓

<br>

**B.Tech**

<br>

Computer Science & Engineering

<br><br>

NSRIT

</td>

<td width="76%" valign="top">

# <font color="#B79BEF">EDUCATION</font>

<font color="#9B7EDE">━━━━━━━━</font>

## B.Tech — Computer Science & Engineering

### NSRIT (Autonomous), Visakhapatnam

Computer Science & Engineering student with a focus on software development, ServiceNow, automation, Full Stack Development and cloud technologies.

<br>

## Training

### Python Full Stack Development — MSME

Focused on Python programming and Full Stack Development concepts.

</td>
</tr>
</table>

---

<table>
<tr>
<td width="24%" valign="top">

### <font color="#9B7EDE">SKILLS</font>

`05`

<br><br>

⚡ ServiceNow

<br>

💻 Development

<br>

🗄️ Database

<br>

☁️ Cloud

<br>

🔧 Tools

</td>

<td width="76%" valign="top">

# <font color="#B79BEF">SKILLS</font>

<font color="#9B7EDE">━━━━━━━━</font>

## ServiceNow

<p>
<img src="https://img.shields.io/badge/ITSM-9B7EDE?style=flat-square"/>
<img src="https://img.shields.io/badge/Service%20Catalog-B79BEF?style=flat-square"/>
<img src="https://img.shields.io/badge/Flow%20Designer-9B7EDE?style=flat-square"/>
<img src="https://img.shields.io/badge/Business%20Rules-B79BEF?style=flat-square"/>
<img src="https://img.shields.io/badge/Client%20Scripts-9B7EDE?style=flat-square"/>
<img src="https://img.shields.io/badge/UI%20Policies-B79BEF?style=flat-square"/>
<img src="https://img.shields.io/badge/ACLs-9B7EDE?style=flat-square"/>
<img src="https://img.shields.io/badge/Update%20Sets-B79BEF?style=flat-square"/>
<img src="https://img.shields.io/badge/Scoped%20Applications-9B7EDE?style=flat-square"/>
</p>

## Programming & Web

<p>
<img src="https://skillicons.dev/icons?i=python,java,js,html,css&theme=dark"/>
</p>

## Database

<p>
<img src="https://skillicons.dev/icons?i=postgresql&theme=dark"/>
</p>

**SQL • PostgreSQL**

## Cloud

**Cloud Computing • AWS Concepts**

## Development Tools

<p>
<img src="https://skillicons.dev/icons?i=git,github,vscode&theme=dark"/>
</p>

</td>
</tr>
</table>

---

# <font color="#B79BEF">CERTIFICATIONS</font>

<font color="#9B7EDE">━━━━━━━━</font>

<table>
<tr>
<td align="center" width="50%">

### ⚡ ServiceNow CSA

**Certified System Administrator**

<img src="https://img.shields.io/badge/CSA-CERTIFIED-9B7EDE?style=for-the-badge"/>

</td>

<td align="center" width="50%">

### 🚀 ServiceNow CAD

**Certified Application Developer**

<img src="https://img.shields.io/badge/CAD-CERTIFIED-B79BEF?style=for-the-badge"/>

</td>
</tr>
</table>

---

# <font color="#B79BEF">GITHUB</font>

<font color="#9B7EDE">━━━━━━━━</font>

<p align="center">

<img src="https://github-stats-extended.vercel.app/api?username=harikajetti20-dev&show_icons=true&theme=tokyonight&hide_border=true"/>

</p>

<p align="center">

<img src="https://github-stats-extended.vercel.app/api/top-langs?username=harikajetti20-dev&layout=compact&theme=tokyonight&hide_border=true"/>

</p>

<p align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=harikajetti20-dev&theme=tokyonight&hide_border=true"/>

</p>

---

<div align="center">

## <font color="#B79BEF">LET'S CONNECT</font>

<font color="#9B7EDE">━━━━━━━━━━━━━━━━━━━━</font>

<br><br>

<a href="https://github.com/harikajetti20-dev">
<img src="https://img.shields.io/badge/GITHUB-18152A?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/harikajetti/">
<img src="https://img.shields.io/badge/LINKEDIN-9B7EDE?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:harikajetti20@gmail.com">
<img src="https://img.shields.io/badge/EMAIL-B79BEF?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=Montserrat&weight=600&size=16&duration=2600&pause=900&color=9B7EDE&center=true&vCenter=true&width=800&height=35&lines=Always+learning.+Always+building.+Always+evolving.+%E2%9C%A8;Turning+ideas+into+working+solutions.+%F0%9F%9A%80&repeat=true"/>

<br><br>

📧 **[harikajetti20@gmail.com](mailto:harikajetti20@gmail.com)**

<br>

📍 **Visakhapatnam, Andhra Pradesh, India**

</div>

<br>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=150&color=0B0812&section=footer&animation=fadeIn" width="100%"/>
</p>
```
