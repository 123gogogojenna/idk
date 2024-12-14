/* Reset some default styles */
body, h1, h2, h3, p {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style-type: none;
    background-color: #333;
    overflow: hidden;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    padding: 0.5rem 1rem;
}

nav ul li a:hover {
    background-color: #575757;
}

section {
    padding: 2rem;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1rem;
    max-width: 400px;
    margin: auto;
}

input, textarea {
    width: 100%;
    padding: 0.5rem;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button {
    background-color: #4CAF50;
    color: white;
    padding: 0.5rem 1rem;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}
