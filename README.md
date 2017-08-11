# React-Jk-Music-Player
react music player component 


#### if you want run example
 - `yarn`
 - `npm run demo`   run example
 
####  use
`npm install react-jinke-music-player`

```javascript
import React from "react"
import ReactDOM from "react-dom"
import ReactJkMusicPlayer from "react-jinke-music-player"

const Demo = ()=>(
    <ReactJkMusicPlayer
        mode="mini"                       //music mode           mini or full
        controllerTitle="jk"                //controller title 
        name="demoName"                    //music name
        cover="http://www.thailandballoonfestival.com/tibf2013/images/HugoSlider1.jpg"                     //music cover
        musicSrc="http://tegos.kz/new/mp3_full/Redfoo_-_New_Thang.mp3"        //music path
    />
)

ReactDOM.render(
    <Demo/>,
    document.getElementById('root')
)
```

###  Because the first time the NPM package is formatted for reference  https://github.com/smronju/React-Music-Player

##### Thank you here