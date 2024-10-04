#square{
    height: 100px;
    width: 100px;
    background-color: royalblue;
    position: relative;
    animation-name: movement;
    animation-duration: 4s;
    animation-delay: 2s;
    animation-iteration-count: 5;
}

@keyframes movement {
    0%{top:0px;left :0px;}
    25%{top:0px;left:100px; height: 100px; width: 100px; border-radius: 50px;}
    50%{top:100px;left:100px;height: 100px; width: 100px; background-color: royalblue; border-radius: 0px;}
    75%{top:100px;left :0px; border-radius: 50%;}
    100%{top:0px; left: 0px;}

}