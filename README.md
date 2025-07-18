# Hi, my name is [Andrew](https://andrewbloese.me) 👋
Software Developer based in Arizona – certified for [Full Stack Engineering](https://www.codecademy.com/profiles/AndrewBloese/certificates/ffd0f42cce1a44e9a0108b365047a0a6) and [Computer Science](https://www.codecademy.com/profiles/AndrewBloese/certificates/05009c20e9174378acd37e6c2d0fbfc4) while pursuing a Bachelor's Degree in Computer Science from Arizona State University. 

When I am not building software, I like to play games, mess around with my 3D printer and listen to music (👀 peep my [spotify](https://open.spotify.com/user/blazethedrummer?si=db18ffd7429b4519)). 

## Connect
I am always open to collaboration and invite anyone who would like to work together to reach out via: 
- ✉️ Email - [dev@andrewbloese.me](mailto:dev@andrewbloese.me).
- 📥 Instagram [@a.blaze1218](https://www.instagram.com/a.blaze1218/)
- 🌐 My Website [Contact Form](https://andrewbloese.me)

## Audio Visualizers 
Some of my favorite projects have been creating audio visualizations. The Web Audio API provides straightforward ways to analyze audio data from files or streams. When used with ThreeJS it is possible to create dynamic scenes that react to music! 
The visualizers perform best on Google Chrome, there is some bugginess in safari when attempting to use the microphone analyser while playing music on the same device. Chrome does not have this issue :)

- ⚠️ **NOTE**: The following visualizers may trigger those with photosentitive epilepsy, visit with caution 🧐


### Hallucinaudio
- Hosted with firebase. 
- Initially built as a way to combine all of my previous visualizers into one place.
- First attempt at using multiple different scenes in the same project. 
- A combination of multiple different visualization scenes, using the user's microphone input to drive animation.
- Toggleable blur/hue-rotate effect using the `tab` key
- Unique settings / color customization option menu for *most* visualizers using the on screen button or the `s` key
- Navigate between scenes using `←`,`→`,`↑`,`↓` keys
<div style="display:flex; flex-wrap: wrap; box-sizing: border-box; align-items: center; gap: 10px">
  <img 
    src="https://firebasestorage.googleapis.com/v0/b/storeshit.appspot.com/o/viz%2Fcubes.gif?alt=media&token=dd3e8867-3135-4660-b662-de67dc6827f1" 
    alt="Cubes visualizer"
  />
  <image 
  src="https://firebasestorage.googleapis.com/v0/b/storeshit.appspot.com/o/viz%2Forb.gif?alt=media&token=6b2cda17-e003-487f-92fe-e6abc4f506eb" 
  alt="Orb visualizer"
  />
  <image 
  src="https://firebasestorage.googleapis.com/v0/b/storeshit.appspot.com/o/viz%2Flines.gif?alt=media&token=7bb5d6f5-28f3-48d4-a4ee-ea4ba7baa33a" 
  alt="Lines visualizer"
  />
    
  <image 
  src="https://firebasestorage.googleapis.com/v0/b/storeshit.appspot.com/o/viz%2Fterrain.gif?alt=media&token=e9cc760a-a0c5-4fc8-a5d5-8256249308fb" 
  alt="Terrain visualizer"
  />
  <image 
  src="https://firebasestorage.googleapis.com/v0/b/storeshit.appspot.com/o/viz%2Fkaleido.gif?alt=media&token=f4ad2d0e-9a6d-4a94-95b7-ce31aa5d11df" 
  alt="Kaleidoscope visualizer"
  />
</div>
    
<!-- Cubes -->
#### CUBES
One of the earliest visualizers I created. Each frequency bin is mapped to a cube which spins and scales based on the volume. 
- settings to adjust the 3 mix colors (high, med, and low frequencies)
- settings to adjust the rotation sensitivity

<!-- Orb-->
#### ORB
Initiallly found at [Orb Audio](https://prismicaudio.web.app), with some minor changes such as...
- filled mesh instead of wireframe
- faster light flashes
- configurable light colors
- customize rotation directions/speed

<!-- Lines -->
#### LINES
Splits the frequency data buffer into a given number of "lines", and stores the averaged volumes in each group in their own ring buffer, to generate the illusion of a moving 3d oscillogram. 
- implemented a `DynamicTube` whose geometry can be "easily" reshaped without generating a new mesh.  

<!-- Terrain  -->
#### TERRAIN
Uses similar approach to the lines visualizer however generates scaled cubes to appear more like voxel terrain. 
- Settings for how "glowy" the scene is
  


### [Orb Audio](https://prismicaudio.web.app)
- Hosted with firebase
- First try using Lighting in ThreeJS, where the lights correspond to the 5 loudest frequencies at the current moment in the audio.
- Microphone analysis only

### [Quasar Audio](https://quasar-audio.web.app)/[Beat Valley Visualizer](https://beat-valley-visualizer.web.app)
- "Beat Valley" was originally created with a customizable color pallete, featuring 3 different perspectives to watch the rings shift and scale to the audio. 
- "Quasar Audio" removed the color pallete functionality and instead introduced excessive hue-rotation on the rings and background. I wanted a more "intense" feeling to the visualizer which the hue rotation definately achieved. 



## Languages and Tools
<div style="display:flex; flex-wrap: wrap; box-sizing: border-box; align-items: center; gap: 20px">
  <img style="width: 50px" src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png?20120221235433" alt="Javascript">
  <img style="width: 50px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Typescript_logo_2020.svg/1024px-Typescript_logo_2020.svg.png" alt="Typescript">
  <img style="width: 50px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/935px-Python-logo-notext.svg.png" alt="Python">
  <img style="width: 50px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/C_Programming_Language.svg/1853px-C_Programming_Language.svg.png" alt="C">
  <img style="height: 60px" src="https://upload.wikimedia.org/wikipedia/en/thumb/3/30/Java_programming_language_logo.svg/242px-Java_programming_language_logo.svg.png" alt="Java">
  <img style="width: 60px" src="https://go.dev/blog/go-brand/Go-Logo/PNG/Go-Logo_Blue.png" alt="Go">
  <img style="width: 60px" src="https://cdn4.iconfinder.com/data/icons/logos-3/512/mongodb-2-1024.png" alt="MongoDB">
  <img style="width: 50px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/97/Sqlite-square-icon.svg/1200px-Sqlite-square-icon.svg.png" alt="SQLite">
  <img style="width: 50px" src="https://wiki.postgresql.org/images/3/30/PostgreSQL_logo.3colors.120x120.png" alt="Postgres">
  <img style="width: 60px" src="https://cdn4.iconfinder.com/data/icons/google-i-o-2016/512/google_firebase-2-1024.png" alt="Firebase">
  <img style="height: 50px" src="https://supabase.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo-preview.50e72501.jpg&w=3840&q=75" alt="Supabase">
</div>









<!--
**andrewbloese-00/andrewbloese-00** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
