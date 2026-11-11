# Hi, I'm Parsa 
<!DOCTYPE html>
<html>
<head>
<style>
body {
    background: #0d1117;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.dna {
    display: flex;
    gap: 12px;
    align-items: center;
    height: 180px;
}

.column {
    display: flex;
    flex-direction: column;
    gap: 5px;
}

.pixel {
    width: 12px;
    height: 12px;
    image-rendering: pixelated;
    animation: twist 1.6s infinite ease-in-out;
}

/* DNA colors */
.blue {
    background: #38bdf8;
}

.pink {
    background: #c084fc;
}

.rung {
    background: #94a3b8;
    width: 12px;
    height: 6px;
    margin-top: 3px;
    margin-bottom: 3px;
    animation: pulse 1.6s infinite ease-in-out;
}

/* Animation */
@keyframes twist {
    0%, 100% {
        transform: translateX(0);
    }
    50% {
        transform: translateX(24px);
    }
}

@keyframes pulse {
    0%, 100% {
        opacity: 1;
    }
    50% {
        opacity: 0.25;
    }
}

/* Different timing for each pixel */
.pixel:nth-child(2),
.rung:nth-child(2) { animation-delay: -0.2s; }

.pixel:nth-child(3),
.rung:nth-child(3) { animation-delay: -0.4s; }

.pixel:nth-child(4),
.rung:nth-child(4) { animation-delay: -0.6s; }

.pixel:nth-child(5),
.rung:nth-child(5) { animation-delay: -0.8s; }

.pixel:nth-child(6),
.rung:nth-child(6) { animation-delay: -1s; }

.pixel:nth-child(7),
.rung:nth-child(7) { animation-delay: -1.2s; }

.pixel:nth-child(8),
.rung:nth-child(8) { animation-delay: -1.4s; }
</style>
</head>

<body>

<div class="dna">

    <div class="column">
        <div class="pixel blue"></div>
        <div class="pixel blue"></div>
        <div class="pixel blue"></div>
        <div class="pixel blue"></div>
        <div class="pixel blue"></div>
        <div class="pixel blue"></div>
        <div class="pixel blue"></div>
        <div class="pixel blue"></div>
    </div>

    <div class="column">
        <div class="rung"></div>
        <div class="rung"></div>
        <div class="rung"></div>
        <div class="rung"></div>
        <div class="rung"></div>
        <div class="rung"></div>
        <div class="rung"></div>
        <div class="rung"></div>
    </div>

    <div class="column">
        <div class="pixel pink"></div>
        <div class="pixel pink"></div>
        <div class="pixel pink"></div>
        <div class="pixel pink"></div>
        <div class="pixel pink"></div>
        <div class="pixel pink"></div>
        <div class="pixel pink"></div>
        <div class="pixel pink"></div>
    </div>

</div>

</body>
</html>


### Biology Student | Aspiring Bioinformatician | Developer

I'm a Cell and Molecular Biology student interested in combining **biology, programming, and technology** to build useful things.

I enjoy learning by building small projects, experimenting with new tools, and turning ideas into practical solutions.

---

###  About Me

-  Studying Cell and Molecular Biology
-  Learning Python and programming fundamentals
-  Interested in Bioinformatics and Computational Biology
-  Exploring Web Development, APIs, and Backend Development

###  Current Focus

- **Python** 
- **Bioinformatics** 
- **Web Development** 

###  Tech Stack & Learning

**Languages & Development**

- Python
- HTML
- CSS
- NumPy
- Pandas
- Matplotlib

**Areas of Interest**

- Bioinformatics
- Data Analysis
- Computational Biology
- Web Development


I'm still learning, experimenting, and building my skills one project at a time.
