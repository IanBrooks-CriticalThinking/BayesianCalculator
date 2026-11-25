<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Updating Calculator: Bayesian Reasoning</title>

<!-- Crude, vibe-coded tool for visually displaying the relationship between variables in Baysian reasoning -->

<style>

body{
    font-family: Arial, Helvetica, sans-serif;
    background:#dff4ff;
    padding:12px;
    margin:0;
}

.container{
    width:1000px;
    margin:auto;
}

.box{
    background:white;
    border:2px solid #888;
    border-radius:8px;
    padding:12px;
    margin-bottom:12px;
}

.title-box{
    text-align:center;
    padding-top:10px;
    padding-bottom:10px;
}

.title-box h1{
    margin:0;
    font-size:28px;
}

.title-box h3{
    margin:4px 0 8px 0;
    font-size:18px;
}

.title-box p{
    margin:4px 0;
}

h1,h2,h3{
    margin-top:0;
    margin-bottom:8px;
}

.row{
    margin-bottom:10px;
}

input[type=text]{
    width:500px;
    padding:5px;
    font-size:15px;
}

.slider-row{
    display:flex;
    align-items:center;
    gap:10px;
}

.slider-row input[type=range]{
    width:280px;
}

.value{
    width:60px;
    font-weight:bold;
}

.output-line{
    margin-bottom:4px;
}

.paragraph{
    margin-top:8px;
    line-height:1.35;
    font-size:14px;
}

.lower-section{
    display:flex;
    gap:12px;
    align-items:stretch;
}

.main-column{
    flex:1;
}

/* EQUATIONS BOX */

.equation-box{
    min-height:185px;
    font-size:13px;
}

.equation-title{
    font-weight:bold;
    margin-top:8px;
    margin-bottom:2px;
}

.equation-formula{
    margin-top:0;
    margin-bottom:4px;
    line-height:1.1;
}

.equation-box hr{
    margin-top:6px;
    margin-bottom:6px;
}

/* OUTPUT BOX */

.output-box{
    min-height:180px;
}

/* CONFIDENCE METER */

.confidence-box{
    width:140px;
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:flex-start;
}

.confidence-title{
    font-size:20px;
    font-weight:bold;
    margin-bottom:4px;
}

.confidence-subtitle{
    font-size:13px;
    text-align:center;
    margin-bottom:10px;
    line-height:1.2;
}

.confidence-track{
    width:50px;
    height:400px;
    border:2px solid black;
    border-radius:10px;
    background:#eeeeee;
    overflow:hidden;
    position:relative;
}

#confidenceFill{
    position:absolute;
    bottom:0;
    width:100%;
    height:50%;
    background:red;
    transition:height 0.3s ease,
               background 0.3s ease;
}

.confidence-label-top,
.confidence-label-bottom{
    font-weight:bold;
    margin:4px;
    font-size:14px;
}

</style>
</head>

<body>

<div class="container">

    <div class="box title-box">

        <h1>Updating Calculator: Bayesian Reasoning</h1>

        <h3>by Ian Brooks</h3>

        <p>
            Instructions: Input h and e using the text boxes and
            input variables using the sliders.
        </p>

    </div>

    <div class="box">

        <h3>Input</h3>

        <div class="row">
            In words, h =
            <input type="text" id="hText">
        </div>

        <div class="row">
            In words, e =
            <input type="text" id="eText">
        </div>

        <div class="row slider-row">
            <label>Prior Prob. P(h) =</label>

            <input
                type="range"
                id="ph"
                min="0"
                max="100"
                value="50">

            <span class="value" id="phValue">50%</span>
        </div>

        <div class="row slider-row">
            <label>P(e|h) =</label>

            <input
                type="range"
                id="peh"
                min="0"
                max="100"
                value="50">

            <span class="value" id="pehValue">50%</span>
        </div>

        <div class="row slider-row">
            <label>P(e|~h) =</label>

            <input
                type="range"
                id="penoth"
                min="0"
                max="100"
                value="50">

            <span class="value" id="penothValue">50%</span>
        </div>

    </div>

    <div class="lower-section">

        <div class="main-column">

            <div class="box equation-box">

                <h3>Equations</h3>
 
		<div class="equation-title">
                    
                </div>
                
		<div class="equation-title">
                    Prior Odds
                </div>

                <div class="equation-formula">
                    P(h) / P(~h)
                </div>

                <div class="equation-title">
                    Strength Factor
                </div>

                <div class="equation-formula">
                    P(e|h) / P(e|~h)
                </div>

                <div class="equation-title">
                    New Odds
                </div>

                <div class="equation-formula">
                    Prior Odds × Strength Factor
                </div>

                <hr>

                <div class="equation-title">
                    Two Ways to Calculate Posterior Probability
                </div>

                <div class="equation-formula">
                    Posterior Probability = (New Odds)/(1 + New Odds)<br>
                          
                </div>

                <div class="equation-formula">
                    Posterior Probability =[P(h) × P(e|h)] / [P(h) × P(e|h) + P(~h) × P(e|~h)]<br>
                         <br>
                    
                </div>

            </div>

            <div class="box output-box">

                <h3>Output</h3>

                <div class="output-line" id="outPh"></div>

                <div class="output-line" id="outPeh"></div>

                <div class="output-line" id="outPenoth"></div>

                <br>

                <div class="output-line" id="priorOdds"></div>

                <div class="output-line" id="strengthFactor"></div>

                <div class="output-line" id="newOdds"></div>

                <br>

                <div class="output-line" id="posterior"></div>

                <div class="paragraph" id="description"></div>

            </div>

        </div>

        <div class="box confidence-box">

            <div class="confidence-title">
                Confidence
            </div>

            <div class="confidence-subtitle">
                Posterior<br>
                Probability
            </div>

            <div class="confidence-label-top">
                100%
            </div>

            <div class="confidence-track">

                <div id="confidenceFill"></div>

            </div>

            <div class="confidence-label-bottom">
                0%
            </div>

        </div>

    </div>

</div>

<script>

function confidenceDescription(p){

    if(p < 65){
        return "with very little confidence.";
    }

    if(p < 80){
        return "with moderate confidence.";
    }

    if(p < 90){
        return "with fairly high confidence.";
    }

    if(p < 97){
        return "with very high confidence.";
    }

    return "with extremely high confidence.";

}

function confidenceColor(p){

    if(p < 40){
        return "rgb(255,0,0)";
    }

    if(p > 90){
        return "rgb(140,210,255)";
    }

    const ratio = (p - 40) / 50;

    const red = Math.round(255 * (1 - ratio));
    const green = Math.round(50 + (100 * ratio));
    const blue = Math.round(255 * ratio);

    return `rgb(${red},${green},${blue})`;

}

function updateCalculator(){

    let h =
        document
            .getElementById("hText")
            .value
            .trim();

    let e =
        document
            .getElementById("eText")
            .value
            .trim();

    if(h === ""){
        h = "h";
    }

    if(e === ""){
        e = "e";
    }

    const phPercent =
        Number(
            document
                .getElementById("ph")
                .value
        );

    const pehPercent =
        Number(
            document
                .getElementById("peh")
                .value
        );

    const penothPercent =
        Number(
            document
                .getElementById("penoth")
                .value
        );

    document
        .getElementById("phValue")
        .innerHTML = phPercent + "%";

    document
        .getElementById("pehValue")
        .innerHTML = pehPercent + "%";

    document
        .getElementById("penothValue")
        .innerHTML = penothPercent + "%";

    const ph = phPercent / 100;
    const pNotH = 1 - ph;
    const peh = pehPercent / 100;
    const penoth = penothPercent / 100;

    let priorOdds;

    if(pNotH === 0){
        priorOdds = Infinity;
    }
    else{
        priorOdds = ph / pNotH;
    }

    let strengthFactor;

    if(penoth === 0){
        strengthFactor = Infinity;
    }
    else{
        strengthFactor = peh / penoth;
    }

    let newOdds;

    if(
        priorOdds === Infinity ||
        strengthFactor === Infinity
    ){
        newOdds = Infinity;
    }
    else{
        newOdds =
            priorOdds *
            strengthFactor;
    }

    let posterior = 0;

    const denominator =
        (ph * peh) +
        (pNotH * penoth);

    if(denominator > 0){

        posterior =
            (ph * peh) /
            denominator;

    }

    const posteriorPercent =
        Number(
            (
                posterior * 100
            ).toFixed(1)
        );

    const confidenceFill =
        document.getElementById(
            "confidenceFill"
        );

    confidenceFill.style.height =
        posteriorPercent + "%";

    confidenceFill.style.background =
        confidenceColor(
            posteriorPercent
        );

    document
        .getElementById("outPh")
        .innerHTML =
        "P(h) = " +
        phPercent +
        "%";

    document
        .getElementById("outPeh")
        .innerHTML =
        "P(e|h) = " +
        pehPercent +
        "%";

    document
        .getElementById("outPenoth")
        .innerHTML =
        "P(e|~h) = " +
        penothPercent +
        "%";

    document
        .getElementById("priorOdds")
        .innerHTML =
        "<b>Prior Odds = </b>" +
        (
            priorOdds === Infinity
            ? "∞"
            : priorOdds.toFixed(3)
        );

    document
        .getElementById("strengthFactor")
        .innerHTML =
        "<b>Strength Factor = </b>" +
        (
            strengthFactor === Infinity
            ? "∞"
            : strengthFactor.toFixed(3)
        );

    document
        .getElementById("newOdds")
        .innerHTML =
        "<b>New Odds = </b>" +
        (
            newOdds === Infinity
            ? "∞"
            : newOdds.toFixed(3)
        );

    document
        .getElementById("posterior")
        .innerHTML =
        "<b>Posterior Probability P(h|e) = "
        +
        posteriorPercent
        +
        "%</b>";

    let paragraph = "";

    if(phPercent > 50){

        paragraph +=
            "Before seeing the evidence I believed that "
            +
            h
            +
            " was true with confidence "
            +
            phPercent
            +
            "%. ";

    }
    else{

        paragraph +=
            "Before seeing the evidence I did not believe that "
            +
            h
            +
            " with confidence "
            +
            (100 - phPercent)
            +
            "%. ";

    }

    paragraph +=
        "Then I saw "
        +
        e
        +
        ". ";

    paragraph +=
        "After seeing this evidence my confidence that "
        +
        h
        +
        " is true was "
        +
        posteriorPercent
        +
        "%. ";

    if(posteriorPercent > 50){

        paragraph +=
            "Now I believe that "
            +
            h
            +
            " "
            +
            confidenceDescription(
                posteriorPercent
            );

    }
    else{

        paragraph +=
            "Now I do not believe that "
            +
            h
            +
            ".";

    }

    document
        .getElementById("description")
        .innerHTML =
        paragraph;

}

document
    .querySelectorAll("input")
    .forEach(
        control =>
        control.addEventListener(
            "input",
            updateCalculator
        )
    );

updateCalculator();

</script>

</body>
</html>
