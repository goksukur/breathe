# Breathe

**Breathe Animation with CSS.**

![](https://github.com/goksukur/breathe/blob/ac1b2170a5aa3b0e7a640c0437edb500dcccdc6c/Breathe.gif)

## CSS

      #breathe {
        background: linear-gradient(90deg, #121212, #121212, #F5F5F5, #F5F5F5);
        background-size: 300%;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        animation: animated_text 32s ease-in-out infinite;
        -moz-animation: animated_text 16s ease-in-out infinite;
        -webkit-animation: animated_text 16s ease-in-out infinite;
        font-size: 100px;
        }

      @keyframes animated_text {
        0% { background-position: 0% 100%; }
        50% { background-position: 100% 100%; }
        100% { background-position: 0% 100%; }
      }

## HTML

        <p id="breathe">▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮</p> 


You can use any symbol, text, emoji etc. instead of "▮" in HTML area.
