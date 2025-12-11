const buttons = document.querySelectorAll("#button");
const body = document.querySelector("body");



buttons.forEach((b) => {
   b.addEventListener("click",function(e){
    console.log(e.target.className);
    let color = e.target.className;

    // USING SWITCH CASE

    switch (color) {
        case "gray":
            body.style.backgroundColor = color;
            break;
            case "white":
                body.style.backgroundColor = color;
                break;
                case "blue":
                    body.style.backgroundColor = color;
                    break;
                    case "yellow":
                        body.style.backgroundColor = color;
                        break;
        default:
            alert("click inside the box");
            break;
    }

    // USING IF ELSE 

    // if(e.target.className == "gray"){
    //     body.style.backgroundColor = e.target.className;
    // }
    // if(e.target.className == "white"){
    //     body.style.backgroundColor = e.target.className;
    // }
    // if(e.target.className == "blue"){
    //     body.style.backgroundColor = e.target.className;
    // }
    // if(e.target.className == "yellow"){
    //     body.style.backgroundColor = e.target.className;
    // }
   });
});
