# Invert-PDF-Colors
Reverse PDF background color from white to black in Chrome

If you fall in love with dark mode.However, you have to read a lot of PDF files every single day and light background makes you uncomfortable.You have came right place

Now , let us go into detail.(〃￣︶￣)人(￣︶￣〃)

1.Right-click on the PDF document which you want to open.

2.Go to Open with > Google Chrome.

3.Press SHIFT + CTRL + I to open the console.

4.Make sure that you’re on the Console tab.

5.Copy the following code and paste it into the console and hit Enter:


          var cover = document.createElement("div");

          let css = `

                    position: fixed;

                    pointer-events: none;

                    top: 0;

                    left: 0;

                    width: 100vw;

                    height: 100vh;

                    background-color: white;

                    mix-blend-mode: difference;

                    z-index: 1;

                    `

          cover.setAttribute("style", css);

          document.body.appendChild(cover);

Don't worry , this effect is not permanent if you close your browser.

The modifications DISAPPEAR as soon as you close the browser or tab.`(*>﹏<*)′
