* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body, html {
    height: 100%;
    font-family: 'Arial', sans-serif;
    background-color: #111;
    color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.container {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
}

.main-content {
    z-index: 2;
}

.title {
    font-size: 80px;
    font-weight: 700;
    margin-bottom: 20px;
    text-transform: uppercase;
    letter-spacing: 2px;
    animation: fadeIn 2s ease-in-out;
}

.subtitle {
    font-size: 24px;
    font-weight: 400;
    margin-bottom: 40px;
    opacity: 0.7;
    animation: fadeIn 2.5s ease-in-out;
}

.cta-button {
    font-size: 18px;
    text-decoration: none;
    padding: 12px 30px;
    border: 2px solid #fff;
    border-radius: 30px;
    color: #fff;
    transition: background-color 0.3s ease, color 0.3s ease;
}

.cta-button:hover {
    background-color: #fff;
    color: #111;
}

@keyframes fadeIn {
    0% {
        opacity: 0;
        transform: translateY(20px);
    }
    100% {
        opacity: 1;
        transform: translateY(0);
    }
}
