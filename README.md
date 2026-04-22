markdown_content = """<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Welcome%20to%20My%20Profile&fontSize=50&fontAlignY=38&animation=twinkling" />
</div>

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&weight=600&size=25&duration=4000&pause=1000&color=00FF99&center=true&vCenter=true&width=800&lines=Hi+there!+👋+I'm+Nimish+Kumar;B.Tech+CSE+%40+KR+Mangalam+University;IoT+%26+Robotics+Enthusiast;AI%2FML+%26+Computer+Vision+Developer;Cinematic+Videography+%26+Photography" alt="Typing SVG" />
</h1>

<div align="center">
  <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="30px">
  <img src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif" width="300" />
</div>

<br/>

## 👨‍💻 About Me

- 🎓 Pursuing B.Tech in **Computer Science and Engineering**.
- 💼 Currently an intern at **CodeAlpha**.
- 🤖 Deeply passionate about bridging the gap between software and hardware through **IoT and Robotics**.
- 📸 When I'm not coding, I'm likely flying drones for cinematic campus footage or organizing university sports events.

<br/>

## 🛠️ Tech Stack & Tools

<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,js,html,css,react,arduino,raspberrypi,github,vscode&perline=10" />
  </a>
</div>

<br/>

## 🚀 Featured Projects

<div align="center">
  
| 🏆 Project | 📜 Description | ⚙️ Tech Stack |
| :--- | :--- | :--- |
| **VisionDrive** | Advanced lane change detection and trajectory analysis system for autonomous navigation. | `<YOLOv8>` `<Python>` `<OpenCV>` |
| **Smart Library Tracker** | Real-time seat occupancy dashboard using hardware sensors to track library availability. | `<ESP32>` `<C++>` `<Web Dashboard>` |
| **Autonomous TurtleBot** | Custom-built vacuum cleaning robot designed for automated navigation in university labs. | `<Raspberry Pi>` `<Sensors>` `<Hardware>` |

</div>

<br/>

## 📊 GitHub Analytics

<div align="center">
  <a href="https://github.com/anuraghazra/github-readme-stats">
    <img src="https://github-readme-stats.vercel.app/api?username=nimishkumar9155-lgtm&show_icons=true&theme=tokyonight&hide_border=true&title_color=00FF99" height="195" />
  </a>
  <a href="https://github.com/anuraghazra/github-readme-streak-stats">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=nimishkumar9155-lgtm&theme=tokyonight&hide_border=true&ring=00FF99&fire=00FF99" height="195" />
  </a>
</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
</div>
"""

file_path = "README_updated.md"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(markdown_content)

print(f"Created {file_path}")
