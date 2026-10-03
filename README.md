<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:0f5132,100:3fb950&height=210&section=header&text=Achmad%20Fauzan&fontColor=e6edf3&fontSize=58&fontAlignY=36&desc=packets%20in%20%C2%B7%20insights%20out&descSize=17&descAlignY=57&animation=fadeIn" alt="Achmad Fauzan" width="100%">

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2600&pause=900&color=3FB950&center=true&vCenter=true&width=680&lines=%24+whoami;mahasiswa+UNNES+yang+doyan+ngoprek;%24+cat+interests.txt;networking+%7C+hardware+%7C+data+%7C+software;%24+echo+%22selamat+datang%2C+enjoy+your+stay%22" alt="terminal intro" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-online-3fb950?style=for-the-badge&labelColor=0d1117" alt="status" />
  <img src="https://img.shields.io/badge/base-Jawa_Tengah,_ID-d29922?style=for-the-badge&labelColor=0d1117" alt="base" />
  <img src="https://img.shields.io/badge/kampus-UNNES-58a6ff?style=for-the-badge&labelColor=0d1117" alt="kampus" />
  <img src="https://komarev.com/ghpvc/?username=AchmadFauzan1156&style=for-the-badge&color=3fb950&label=visitors" alt="visitors" />
</p>

<br/>

## 🖥️ `$ neofetch`

```text
        .--.           achmad@fauzan
       |o_o |          ─────────────────────────────────────
       |:_/ |          OS        Mahasiswa · Universitas Negeri Semarang
      //   \ \         Host      Jawa Tengah, Indonesia
     (|     | )        Kernel    networking + hardware
    /'\_   _/`\        Shell     data processing & software
    \___)=(___/        Uptime    on GitHub since Aug 2024
                       Packages  Go · Kotlin · C++ · JavaScript · Python
                       Motto     pelan-pelan asal konsisten
```

> **TL;DR** — hati di hardware, tangan di software. I like knowing how things connect, dari kabel sampai kode.

<br/>

## 🧬 `$ cat about.go`

```go
package main

func main() {
    me := Developer{
        Name:      "Achmad Fauzan",
        Campus:    "Universitas Negeri Semarang",
        Interests: []string{"networking", "hardware", "mikrokontroler"},
        DailyWork: []string{"data processing", "software development"},
        Learning:  []string{"Golang", "Kotlin", "OpenGL"},
        OpenTo:    []string{"kolaborasi", "diskusi", "project iseng yang serius"},
    }

    for me.IsCurious() {
        me.Learn()
        me.Build()
        me.Ngeteh() // wajib, bukan opsional
    }
}
```

<br/>

## 🗺️ `$ nmap --topology fauzan`

Kalau yang saya kerjakan digambar sebagai jaringan, kira-kira begini. Satu gateway, tiga switch, tiap project punya VLAN sendiri:

```mermaid
flowchart TB
    NET(["☁️ internet"]) --- GW{{"🛜 fauzan · gateway"}}

    GW --- SW1["🔀 switch-kuliah"]
    GW --- SW2["🔀 switch-project"]
    GW --- SW3["🔀 switch-ngoprek"]

    subgraph V10["VLAN 10 · Grafika Komputer"]
        OGL["🎨 OpenGL<br/>C++ · GLFW · GLAD · stb_image<br/>shader, texture, uniform · CMake"]
    end

    subgraph V20["VLAN 20 · Pemrograman Web"]
        GO["🐹 Golang<br/>net/http · html/template<br/>routing, form, template"]
    end

    subgraph V30["VLAN 30 · StudyFlow"]
        direction LR
        SFC["📱 client<br/>Kotlin Multiplatform<br/>Android + Desktop"]
        SFA["⚙️ backend<br/>Python · FastAPI"]
        SFD[("PostgreSQL + pgvector<br/>Supabase Auth")]
        SFG["✨ Gemini API"]
        SFC --> SFA
        SFA --> SFD
        SFA --> SFG
    end

    subgraph V40["VLAN 40 · StokAja"]
        direction LR
        STF["🛒 frontend<br/>Next.js · React · Tailwind"]
        STB["📦 backend<br/>Express · JWT · Socket.IO"]
        STD[("MongoDB")]
        STF --> STB
        STB --> STD
    end

    subgraph V50["VLAN 50 · Lab"]
        LAB["🔧 networking & hardware<br/>ESP32 · Docker"]
    end

    SW1 --- V10
    SW1 --- V20
    SW2 --- V30
    SW2 --- V40
    SW3 --- V50
```

<br/>

## ⚙️ `$ top`

```text
PID   TASK                              STATE      NOTE
001   belajar Golang web service        running    semester ini
002   ngulik networking & hardware      running    hobi yang nggak pernah selesai
003   tugas kuliah                      running    priority: realtime
004   tidur cukup                       sleeping   segmentation fault
```

<br/>

## 🧰 `$ ls ~/toolbox`

<p align="center">
  <img src="assets/go.svg" alt="Go" width="104" />
  <img src="assets/kotlin.svg" alt="Kotlin" width="104" />
  <img src="assets/cpp.svg" alt="C++" width="104" />
  <img src="assets/javascript.svg" alt="JavaScript" width="104" />
  <img src="assets/python.svg" alt="Python" width="104" />
</p>

<table>
  <tr>
    <td width="170"><b>Web</b></td>
    <td>
      <img src="https://img.shields.io/badge/Next.js-0d1117?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
      <img src="https://img.shields.io/badge/React-0d1117?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
      <img src="https://img.shields.io/badge/Tailwind-0d1117?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4" alt="Tailwind CSS" />
      <img src="https://img.shields.io/badge/Express-0d1117?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
      <img src="https://img.shields.io/badge/FastAPI-0d1117?style=for-the-badge&logo=fastapi&logoColor=009688" alt="FastAPI" />
    </td>
  </tr>
  <tr>
    <td><b>Data</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/MongoDB-0d1117?style=for-the-badge&logo=mongodb&logoColor=47A248" alt="MongoDB" />
      <img src="https://img.shields.io/badge/Supabase-0d1117?style=for-the-badge&logo=supabase&logoColor=3FCF8E" alt="Supabase" />
    </td>
  </tr>
  <tr>
    <td><b>Hardware & Grafis</b></td>
    <td>
      <img src="https://img.shields.io/badge/ESP32-0d1117?style=for-the-badge&logo=espressif&logoColor=E7352C" alt="ESP32" />
      <img src="https://img.shields.io/badge/OpenGL-0d1117?style=for-the-badge&logo=opengl&logoColor=5586A4" alt="OpenGL" />
    </td>
  </tr>
  <tr>
    <td><b>Tools</b></td>
    <td>
      <img src="https://img.shields.io/badge/Git-0d1117?style=for-the-badge&logo=git&logoColor=F05032" alt="Git" />
      <img src="https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=2496ED" alt="Docker" />
      <img src="https://img.shields.io/badge/CMake-0d1117?style=for-the-badge&logo=cmake&logoColor=white" alt="CMake" />
      <img src="https://img.shields.io/badge/Android_Studio-0d1117?style=for-the-badge&logo=androidstudio&logoColor=3DDC84" alt="Android Studio" />
      <img src="https://img.shields.io/badge/Vercel-0d1117?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
    </td>
  </tr>
</table>

<br/>

## 📂 `$ ls -l ~/projects`

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📚 <a href="https://github.com/AchmadFauzan1156/StudyFlow">StudyFlow</a></h3>
      <p>Aplikasi Android untuk bantu ngatur alur belajar, biar deadline nggak datang tiba-tiba.</p>
      <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
      <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android" />
      <img src="https://img.shields.io/github/last-commit/AchmadFauzan1156/StudyFlow?style=flat-square&color=3fb950&labelColor=0d1117" alt="last commit" />
    </td>
    <td width="50%" valign="top">
      <h3>🎨 <a href="https://github.com/AchmadFauzan1156/OpenGL">OpenGL</a></h3>
      <p>Catatan dan eksperimen computer graphics — from a single triangle to something that moves.</p>
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
      <img src="https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white" alt="OpenGL" />
      <img src="https://img.shields.io/github/last-commit/AchmadFauzan1156/OpenGL?style=flat-square&color=3fb950&labelColor=0d1117" alt="last commit" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📦 <a href="https://github.com/AchmadFauzan1156/stokaja-backend">StokAja · Backend</a></h3>
      <p>API di balik sistem manajemen stok StokAja.</p>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
      <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
      <img src="https://img.shields.io/github/last-commit/AchmadFauzan1156/stokaja-backend?style=flat-square&color=3fb950&labelColor=0d1117" alt="last commit" />
    </td>
    <td width="50%" valign="top">
      <h3>🛒 <a href="https://github.com/AchmadFauzan1156/stokaja-frontend">StokAja · Frontend</a></h3>
      <p>Sisi pengguna dan dashboard admin StokAja, dua-duanya sudah live.</p>
      <a href="https://stokaja-frontend.vercel.app"><img src="https://img.shields.io/badge/demo-user-3fb950?style=flat-square&logo=vercel&logoColor=white&labelColor=0d1117" alt="demo user" /></a>
      <a href="https://stokaja-admin-frontend.vercel.app"><img src="https://img.shields.io/badge/demo-admin-d29922?style=flat-square&logo=vercel&logoColor=white&labelColor=0d1117" alt="demo admin" /></a>
      <a href="https://github.com/AchmadFauzan1156/stokaja-admin-frontend"><img src="https://img.shields.io/badge/repo-admin-58a6ff?style=flat-square&logo=github&logoColor=white&labelColor=0d1117" alt="repo admin" /></a>
    </td>
  </tr>
</table>

<br/>

## 📈 `$ uptime --stats`

<p align="center">
  <img src="https://streak-stats.demolab.com?user=AchmadFauzan1156&hide_border=true&background=0D1117&ring=3FB950&fire=D29922&currStreakLabel=3FB950&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E" alt="streak" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AchmadFauzan1156&layout=donut&hide_border=true&bg_color=0D1117&title_color=3FB950&text_color=C9D1D9" alt="top languages" height="170" />
</p>

<details>
  <summary><b>📊 Grafik kontribusi (klik untuk buka)</b></summary>
  <br/>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AchmadFauzan1156&bg_color=0d1117&color=3fb950&line=3fb950&point=d29922&area=true&area_color=3fb950&hide_border=true" alt="activity graph" width="100%" />
</details>

<br/>

## 📡 `$ ping fauzan`

```text
PING fauzan (github.com/AchmadFauzan1156): 56 data bytes
64 bytes: ada ide project?        → buka issue, ayo dibahas
64 bytes: nemu bug?               → kabari, nanti saya benerin
64 bytes: mau ngobrol jaringan?   → gas, kapan aja

--- fauzan ping statistics ---
3 packets transmitted, 3 received, 0% packet loss
```

<p align="center">
  <a href="https://github.com/AchmadFauzan1156"><img src="https://img.shields.io/badge/follow-@AchmadFauzan1156-3fb950?style=for-the-badge&logo=github&labelColor=0d1117" alt="follow" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3fb950,55:0f5132,100:0d1117&height=110&section=footer&text=exit%200%20%C2%B7%20terima%20kasih%20sudah%20mampir&fontColor=e6edf3&fontSize=15&fontAlignY=72" alt="exit 0" width="100%">
