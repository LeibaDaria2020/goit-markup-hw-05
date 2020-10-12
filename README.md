.box:nth-child(2) {
/_ transform: translateY(110px); _/

animation: animateY110 3000ms infinite 1000ms;
background-color: #03a9f4;
}

.box:nth-child(2)::before {
content: "translateY(110px)";
}

@keyframes animateY110 {
0% {
transform: translateY(0);
}

50% {
transform: translateY(110px);
}

100% {
transform: translateY(0);
}
}
