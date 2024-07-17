# Line Following Robot
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Name** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Allison P | KIPP NYC College Prep | Mechanical Engineering | Incoming Senior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My final milestone consisted of me coding the robot to be able to adjust its speed as it follows a black line with a remote control. This took me a while to complete due to the robot’s speed never actually adjusting. I kept thinking the answer towards this error was more complicated than it actually was, hence why I took longer than I had anticipated. However, the answer was as simple as the initial speed of the robot being in the void loop () function, causing the robot’s initial speed to become unchangeable. This moment definitely taught me that some solutions are simpler than one may think. During my overall time in this program, I’ve faced a lot of problems and even some doubts that I’ll be able to finish this project, however thanks to perseverance I was taught that anything was possible thanks to hard work and dedication. I hope to take my knowledge from BlueStamp to learn more about coding, so that I’m able to eventually implement that onto my future builds. 



# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/o2IOYAsA8n0?si=dx2H_BiItkd1xtwh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


  My second milestone consisted of me finishing wiring and coding my robot to detect a black line along with starting to brainstorm and begin working on adding innovative ideas onto my build. While I completed the wiring effortlessly, the coding part was where I began going through some real troubles due to some issues with the analogWrite() functions in my code, which can cause issues with the robot’s sense of directions and motors; in my case, it caused the robot to move backwards rather than forward. However once I’ve noticed this error it became easy to get rid of! Then I’ve moved onto brainstorming new innovative ideas for my build, which led me to the conclusion of adding a remote control so that my robot is able to move at different speeds as it follows a line. Before adding more onto my original code, I decided to test if the wiring and coding for the remote control was accurate by creating a separate code that solely focuses on the robot’s ability to move based on given instructions from the remote control. Luckily, this went along smoothly and for my third milestone, as said previously, I hope to combine both previous codes to create a line following robot that can increase or decrease its speed once instructed to by the remote control. 


# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/rwWfh26CdAY?si=LXISGsjKZZFyQUD3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

  My first milestone was assembling my build and running a test code in order to certify that the robot was able to move. However before completing my actual build, I’ve done a slight simple practice with coding the LED to light on and off to obtain a bit of a reminder and just a better overall understanding of the Arduino and breadboard. In terms of assembling the robot, I had to improvise a bit due to the screws and standoffs' sizes not aligning with the video tutorial I used to assemble my robot, however it did end up working despite the sizes slightly differing from the video. My test code consists of a loop where my robot moves in all of the same directions on repeat. While, the robot is currently able to move in all directions, it currently can't follow a black line. My current future goals are to focus on coding the robot to follow a black line and to brainstorm more unique and new innovated ideas to add onto my build. 

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| SunFounder Ultimate Starter Kit | Main Build | $69.99 | <https://www.amazon.com/SunFounder-Compatible-Tutorials-Including-Controller/dp/B0B778L1DZ/ref=sr_1_1?crid=3JQTX3SPFIY9Z&dib=eyJ2IjoiMSJ9.D9LrCZJnua_keVMLJz2FWi87-vYq5Z0c0hghVjdTqVV5SxTVgutlUut8NIgJpkDha5RIUUEOd8ZL_9-liu4TuIX3Y5c9E3mrmlKMD_2d9cnuKu55yBqRD35FcNSR2oUIVkT7byKksfuqXVAx34A8gUuPMYKaM3Jepu1QA3uOutR5sR0O3bugifITwp4OocPwYE4ZDNZaCae7Y3Ydd5zuneo_8PLiYwbdyVH9QvcGEwg.-iuZvwFJywFFRggszeNpXLuAEE8nPtLKbqmhVUOfLc0&dib_tag=se&keywords=sunfounder+3+in+1+starter+kit+for+arduino+uno&qid=1718980379&sprefix=3+in+1+ard%2Caps%2C120&sr=8-1">  </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Project Guide]([https://trashytuber.github.io/YimingJiaBlueStamp/](https://docs.sunfounder.com/projects/3in1-kit-v2/en/latest/))
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)

