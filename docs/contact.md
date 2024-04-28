# Contact me

If you have any feedback or questions, please feel free to contact me using the form below:
<style>
.contact-form {
    max-width: 400px;
    margin: 50px 0 0 0; /* Adjusted margin for left alignment */
    padding: 40px;
    border-radius: 10px;
    background-color: #343a40; /* Dark background color */
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1), 0 1px 3px rgba(0, 0, 0, 0.08);
}

.contact-form .form-group {
    margin-bottom: 20px;
}

.contact-form label {
    font-weight: bold;
    color: #fff; /* White text color */
}

.contact-form input[type="email"] {
    width: 100%;
    padding: 10px;
    border: 1px solid #ced4da;
    border-radius: 5px;
    box-sizing: border-box;
    background-color: #e9ecef; /* Light background color for input */
    color: #495057; /* Text color for input */
}

.contact-form button[type="submit"] {
    padding: 12px;
    border: none;
    border-radius: 5px;
    background-color: #007bff; /* Blue button color */
    color: #fff;
    font-size: 16px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.contact-form button[type="submit"]:hover {
    background-color: #0056b3; /* Darker blue color on hover */
}
</style>

<div class="contact-form">
    <form action="mailto:jangetipranay@gmail.com" method="post" enctype="text/plain">
        <div class="form-group">
            <label for="email">Email:</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
        </div>
        <button type="submit" class="btn btn-primary btn-block">Send</button>
    </form>
</div>
<br>


<div id="social-media" class="hover-color">
    <span>P</span><span>l</span><span>e</span><span>a</span><span>s</span><span>e</span>
    <span>f</span><span>o</span><span>l</span><span>l</span><span>o</span><span>w</span>
    <span>m</span><span>e</span>
    <span>o</span><span>n</span>
    <span>S</span><span>o</span><span>c</span><span>i</span><span>a</span><span>l</span>
    <span>M</span><span>e</span><span>d</span><span>i</span><span>a</span>
</div>
<script>
    document.addEventListener('DOMContentLoaded', function() {
        const letters = document.querySelectorAll('.hover-color span');
        setInterval(function() {
            letters.forEach(letter => {
                const randomColor = getRandomColor();
                letter.style.color = randomColor;
            });
        }, 500); // Change color every 500 milliseconds (0.5 seconds)
    });

    function getRandomColor() {
        const letters = '0123456789ABCDEF';
        let color = '#';
        for (let i = 0; i < 6; i++) {
            color += letters[Math.floor(Math.random() * 16)];
        }
        return color;
    }
</script>


:fontawesome-brands-instagram:{.instagram}: [Instagram](https://www.instagram.com/pranay__sai) 
:fontawesome-brands-linkedin:{.linkedin}: [LinkedIn](https://www.linkedin.com/in/pranay-sai-j) 
:fontawesome-brands-facebook:{.facebook}: [Facebook](https://www.facebook.com/pranay.sai.7798) 


