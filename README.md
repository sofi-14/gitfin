body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f4f8fb;
    color: #333;
}

header {
    background: linear-gradient(135deg, #73cde8, #4aaed1);
    color: white;
    text-align: center;
    padding: 30px 20px;
}

.card {
    background: white;
    padding: 20px;
    margin: 20px 0;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

.animal {
    background: white;
    padding: 15px;
    border-radius: 12px;
    width: 220px;
    text-align: center;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    transition: transform 0.3s, box-shadow 0.3s;
}

.animal:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 15px rgba(0,0,0,0.15);
}

button {
    background-color: #73cde8;
    color: white;
    border: none;
    padding: 10px 15px;
    border-radius: 8px;
    cursor: pointer;
    font-weight: bold;
}

button:hover {
    background-color: #4aaed1;
}
