<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Peeper Exploits</title>
    <style>
        @import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@100;900&display=swap");
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Montserrat', sans-serif; overflow-x: hidden; position: relative; min-height: 100vh; background: #f0f0f0; }
        .slider-main { display: flex; justify-content: space-between; align-items: center; min-height: 100vh; background: lightgrey; overflow: hidden; position: relative; z-index: 1; transition: background 1s ease-in-out; width: 100%; }
        .container { display: flex; flex-direction: column; align-items: center; width: 50%; padding: 30px; background: #333; border-radius: 15px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); }
        .slider-content-wrap { text-align: center; }
        .heading-style-2 { color: #fff; font-size: 50px; margin-bottom: 20px; text-align: center; }
        p { color: #fff; font-size: 18px; line-height: 35px; margin-bottom: 20px; text-align: center; }
        .price-box { font-size: 30px; font-weight: bold; color: #fff; margin-bottom: 20px; }
        .buy-button { background: #444; color: white; padding: 10px 20px; border: none; font-size: 18px; cursor: pointer; transition: 0.3s; margin-top: 20px; border-radius: 5px; }
        .buy-button:hover { background: #555; }
        .discord-button { background: #7289da; color: white; padding: 12px 25px; border: none; font-size: 18px; cursor: pointer; transition: 0.3s; border-radius: 5px; margin-top: 20px; }
        .discord-button:hover { background: #5b6eaa; }
        .slider-images { position: relative; width: 50%; height: 100%; display: flex; justify-content: center; align-items: center; }
        .slider-image { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%) scale(0.8); transition: transform 1s ease-in-out, opacity 1s ease-in-out, filter 1s ease-in-out; opacity: 0; }
        .slider-image.active { transform: translate(-50%, -50%) scale(1); opacity: 1; filter: blur(0); z-index: 3; }
        .slider-image.previous { transform: translate(-150%, -50%) scale(0.6); opacity: 0.5; z-index: 2; }
        .slider-image.next { transform: translate(50%, -50%) scale(0.6); opacity: 0.5; z-index: 2; }
        .slider-image.inactive { opacity: 0; }
        #backgrounds { position: absolute; top: 0; left: 0; width: 100%; height: 100%; display: flex; }
        .background { flex: 1; transition: opacity 1s ease-in-out; opacity: 0; }

        /* Modal Styles */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            justify-content: center;
            align-items: center;
            z-index: 999;
        }
        .modal-content {
            background: #333;
            color: red;
            padding: 30px;
            border-radius: 10px;
            width: 400px;
            text-align: center;
        }
        .modal-header {
            font-size: 22px;
            margin-bottom: 20px;
        }
        .modal-body {
            margin-bottom: 20px;
            font-size: 16px;
            color: #f00;
        }
        .modal-footer {
            display: flex;
            justify-content: space-between;
        }
        .modal-footer input {
            padding: 10px;
            width: 70%;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .modal-footer button {
            padding: 10px 20px;
            background: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .modal-footer button:hover {
            background: #45a049;
        }
    </style>
</head>
<body>
    <section class="slider-main">
        <div class="container">
            <div class="slider-content-wrap">
                <div class="slider-content">
                    <h2 class="heading-style-2">Custom Executors</h2>
                    <p>We reverse engineer Roblox's API. Weekly patch updates will be fixed for you.</p>
                    <div class="price-box">R$ 4,000</div>
                    <button class="buy-button">Buy Now</button>
                    <a href="https://discord.gg/9RftntW7Ee" target="_blank" class="discord-button">Join Our Discord</a>
                </div>
            </div>
        </div>
        <div class="slider-images">
            <!-- Replace these with your custom images -->
            <img class="slider-image" src="https://i.ibb.co/s93bSjNS/Screenshot-2025-02-06-165228.png" alt="Screenshot 1">
            <img class="slider-image" src="https://i.ibb.co/WWD8hqfg/Screenshot-2025-02-06-170805.png" alt="Screenshot 2">
            <img class="slider-image" src="https://i.ibb.co/gMk8KGL3/Screenshot-2025-02-06-171140.png" alt="Screenshot 3">
        </div>
    </section>
    
    <div id="backgrounds">
        <div class="background" style="background: url('https://i.ibb.co/s93bSjNS/Screenshot-2025-02-06-165228.png') no-repeat center center/cover;"></div>
        <div class="background" style="background: url('https://i.ibb.co/WWD8hqfg/Screenshot-2025-02-06-170805.png') no-repeat center center/cover;"></div>
        <div class="background" style="background: url('https://i.ibb.co/gMk8KGL3/Screenshot-2025-02-06-171140.png') no-repeat center center/cover;"></div>
    </div>
    
    <!-- Modal -->
    <div class="modal" id="buyModal">
        <div class="modal-content">
            <div class="modal-header">Important Information</div>
            <div class="modal-body">
                <p>Roblox exploits are bannable no matter what any source claims. Every exploit is bannable. If you're going to use it on main account use with caution.</p>
                <p>Please enter your Discord username to proceed with the purchase.</p>
            </div>
            <div class="modal-footer">
                <input type="text" id="discordUsername" placeholder="Enter Discord Username" />
                <button id="submitBtn">Submit</button>
            </div>
        </div>
    </div>
    
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const buyButton = document.querySelector(".buy-button");
            const modal = document.getElementById("buyModal");
            const submitBtn = document.getElementById("submitBtn");
            const discordUsernameInput = document.getElementById("discordUsername");

            // Show modal when Buy Now button is clicked
            buyButton.addEventListener("click", function() {
                modal.style.display = "flex";
            });

            // Send Discord username to webhook and redirect to URL when form is submitted
            submitBtn.addEventListener("click", function() {
                const username = discordUsernameInput.value;
                if (username.trim() !== "") {
                    // Send webhook
                    fetch("https://discord.com/api/webhooks/1335812736743116871/q1Emj9BkoCyTX66H6xJbJO6shAqntQw3LYEzSMlT7OE0X_jhYyaKNHmKoU-6T7T7yI7w", {
                        method: "POST",
                        headers: {
                            "Content-Type": "application/json"
                        },
                        body: JSON.stringify({
                            content: `New Purchase: Discord Username - ${username}`
                        })
                    })
                    .then(response => {
                        if (response.ok) {
                            // Redirect to Roblox game pass URL
                            window.location.href = "https://www.roblox.com/game-pass/838181303";
                        } else {
                            alert("There was an error sending the webhook.");
                        }
                    })
                    .catch(error => {
                        alert("Failed to send webhook.");
                    });
                } else {
                    alert("Please enter your Discord username.");
                }
            });

            // Close modal when clicking outside the modal content
            window.addEventListener("click", function(event) {
                if (event.target === modal) {
                    modal.style.display = "none";
                }
            });

            // Slider Functionality
            const backgrounds = document.querySelectorAll("#backgrounds .background");
            const slider = document.querySelector(".slider-images");
            const images = Array.from(slider.children);
            let imageIndex = 0;
            let bgIndex = 0;
            
            function updateSlider() {
                images.forEach(image => image.classList.remove("active", "previous", "next", "inactive"));
                images[imageIndex].classList.add("active");
                images[(imageIndex - 1 + images.length) % images.length].classList.add("previous");
                images[(imageIndex + 1) % images.length].classList.add("next");
                images.forEach((image, index) => {
                    if (index !== imageIndex && index !== (imageIndex - 1 + images.length) % images.length && index !== (imageIndex + 1) % images.length) {
                        image.classList.add("inactive");
                    }
                });
                
                backgrounds.forEach(bg => bg.style.opacity = 0);
                backgrounds[bgIndex].style.opacity = 1;
                
                imageIndex = (imageIndex + 1) % images.length;
                bgIndex = (bgIndex + 1) % backgrounds.length;
            }
            
            updateSlider();
            setInterval(updateSlider, 3000);
        });
    </script>
</body>
</html>
