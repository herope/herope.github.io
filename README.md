# herope.github.io
@font-face {
    font-family: "leaf";
    src: url(./Css/LeaffuseDemo-Wym3G.ttf);
}
@font-face {
    font-family: "other";
    src: url(./Css/ReenieBeanie-Regular.ttf);
}
@font-face {
    font-family: "newleaf";
    src: url(./Css/ThefotosintesisItalic-MVAWw.ttf);
}
@font-face {
    font-family: "cool";
    src: url(./Css/AneliyaPersonalUse-6YvLx.ttf)
}
@font-face {
    font-family: "lain";
    src: url(./Css/Lovelt__.ttf);
}
@font-face {
    font-family: "curvy";
    src: url(./Css/APlainerFont-aL7R.ttf);
}
body {
    font-family: "curvy";
    font-size: 2vw;
    color: #d0d0f3;
    background: url(./bg.jpg) center/cover;
    min-height: 100vh;
    margin: 20px;
}
h1 {
    color: #d0d0f3;
    text-align: center;
text-transform: capitalize;
letter-spacing: 2px;
font-size: 4vw;
text-shadow: 3px 3px 2px #d0d0f354;
font-family: "newleaf";
}
.leaf-color {
    color: lightgreen;
    text-shadow: 3px 3px 2px #8ee98e61;
}
.pleut {
    text-shadow: 3px 3px 4px rgba(64, 224, 208, 0.3), -3px -3px 4px rgba(64, 224, 208, 0.3), 3px -3px 4px rgba(64, 224, 208, 0.3), -3px 3px 4px rgba(64, 224, 208, 0.3);
    position: relative;
    background: url(./blue\ rain.gif) center center no-repeat rgba(197, 197, 245, 0.322);
    display: inline-block; 
    border-radius: 10px;

}
.gentil {
    border: 2px solid cornsilk;
    border-radius: 30px;
    padding: 2px 10px 2px 10px;
    background: #e7e7ec48;
    box-shadow: inset 0px 0px 20px 2px #657fc8f7;
}
.gentil li {
    list-style: none;
    margin: 5px;
    padding: 5px;
    background: #5f78ea42;
    border-radius: 10px;
    height: 50px;
    width: 100px;
    font-size: 3vw;
    display: flex;
    justify-content: center;
    align-items: center;
}
.gentil ul {
    display: flex;
    justify-content: space-around;
}
.grosseboite {
    position: relative;
    background: url(./blue\ rain.gif) center center no-repeat rgba(197, 197, 245, 0.322);
    display: inline-block;
    background-size: cover;
    border: #d0d0f3;
    border-radius: 10px;
}
.question {
    display: grid;
    grid-template-columns: 20% 80%;
    background: #938ae088;
    padding: 10px;
    border-radius: 20px;
    border: 2px solid cornsilk;
}
.question img {
    width: 50%;
    margin: auto;
    display: block;
}
#btnsubmit {
    margin-top: 20px;
    cursor: pointer;
    width: 100px;
    height: 25px;
    position: relative;
    left: 40%;
    transform: translateX(-50%);
}
#btnsubmit:hover {
    background: #6d6df0;
    color: #d0d0f3;
}
@media screen and (max-width: 370px) {
    .gentil ul {
        display: flex;
        flex-direction: column;
    align-items: center;
    }
}
@media screen and (max-width: 500px) {
    .question {
        display: block;
        width: 50%;
        margin: auto;
    }
    #btnsubmit {
        left: 50%;
    transform: translateX(-50%);
    }
}
.lapin {
    display: grid;
    grid-template-columns: 40% 60%;
    background: rgba(136, 231, 136, 0.356);
    margin-top: 20px;
    padding: 10px;
    border-radius: 20px;
    border: 2px solid cornsilk;
}
.lapin video {
    width: 90%;
    margin: auto;
    display: block;
}
.lapin p {
    font-size: 1.5vw;
}
