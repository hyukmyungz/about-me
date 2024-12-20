<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>about me</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffc0cb;
            margin: 0;
            padding: 20px;
            animation: fadeInPage 1.5s ease-in-out; /* Fade-in animation for the whole page */
        }

        @keyframes fadeInPage {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        /* General fade-in animation for all elements */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px); /* Adds a subtle upward motion */
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .container {
            background-color: white;
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border: 1px solid #fcc;
            text-align: justify;
            animation: fadeIn 1.5s ease-in-out; /* Fade-in effect for the container */
        }

        h2, h3 {
            text-transform: lowercase;
            margin-bottom: 10px;
            text-align: center;
            animation: fadeIn 1.8s ease-in-out; /* Delayed fade-in for headers */
        }

        h2 {
            border-bottom: 1px solid #f99;
        }

        .profile {
            display: flex;
            align-items: flex-start;
            margin-bottom: 20px;
            animation: fadeIn 2s ease-in-out; /* Delayed fade-in for the profile section */
        }

        .profile img {
            border-radius: 8px;
            margin-right: 20px;
            width: 120px;
            height: auto;
            animation: fadeIn 2.2s ease-in-out; /* Fade-in effect for the profile image */
        }

        .profile-info {
            line-height: 1.6;
            text-align: justify;
            animation: fadeIn 2.4s ease-in-out; /* Fade-in effect for profile text */
        }

        .center-intro {
            text-align: center;
            font-size: 1.1em;
            margin-bottom: 10px;
            animation: fadeIn 2.6s ease-in-out; /* Delayed fade-in for intro text */
        }

        table {
            width: 100%;
            margin-bottom: 20px;
            animation: fadeIn 2.8s ease-in-out; /* Fade-in for tables */
        }

        th {
            color: #ff69b4;
            font-size: 1em;
            padding-bottom: 10px;
            text-align: center;
            font-weight: bold;
            animation: fadeIn 3s ease-in-out; /* Delayed fade-in for table headers */
        }

        td {
            padding: 10px 0;
            text-align: justify;
            animation: fadeIn 3.2s ease-in-out; /* Fade-in for table content */
        }

        ul {
            list-style-type: none;
            padding: 0;
            animation: fadeIn 3.4s ease-in-out; /* Fade-in for unordered lists */
        }

        ul li {
            padding: 5px 0;
            animation: fadeIn 3.6s ease-in-out; /* Slightly delayed fade-in for list items */
        }

        ul li:before {
            content: "•";
            color: #ff69b4;
            display: inline-block; 
            width: 1em;
        }

        .decorative-line {
            color: #ff69b4;
            text-align: center;
            margin-bottom: 10px;
            font-size: 1.2em;
            animation: fadeIn 3.8s ease-in-out; /* Fade-in for decorative lines */
        }

        .center-text {
            text-align: center;
            animation: fadeIn 4s ease-in-out; /* Fade-in for centered text */
        }

        /* New styles for the "Where to Find Me" section */
        .hidden {
            display: none;
        }

        .where-to-find-me {
            margin-top: 20px;
            animation: fadeIn 4.2s ease-in-out; /* Fade-in for this section */
        }

        /* Adjusting the h3 styles for "Where to Find Me" */
        .where-to-find-me h3 {
            color: #ff69b4; /* Match the <th> color */
            font-size: 1em; /* Match the <th> font size */
            font-weight: bold; /* Match the <th> font weight */
            text-align: center; /* Match the <th> alignment */
            padding-bottom: 10px; /* Match the <th> padding */
            margin: 0; /* Remove extra margin */
            cursor: pointer;
            animation: fadeIn 4.4s ease-in-out;
        }

        .where-to-find-me h3:hover {
            background-color: transparent; /* Remove hover background for consistency */
        }

        .find-me-content {
            margin-top: 10px;
            padding: 10px;
            background-color: #fff;
            border: 1px solid #fcc;
            border-radius: 5px;
        }

        /* Match the color of "where to find me" */
        .find-me-content strong {
            color: #ff69b4;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>about me</h2>
        <div class="profile">
            <img src="https://cdn.discordapp.com/attachments/1310616777751007384/1310616862652104804/20141144732.jpg?ex=6745de92&is=67448d12&hm=54a65feb6b34a3f9ac44763dfa1591488d7e15d19f7e6f203d0c0b02203583b9&" alt="profile picture">
            <div class="profile-info">
                <div class="center-intro">
                    <strong style="color: #f79ac0;">jana<span style="font-style: italic;">!</span></strong> or <strong style="color: #f79ac0;">nana</strong> ᓚ₍⑅^..^₎♡ she/her 20 leo istp
                </div>
                <strong>likes</strong>: bnd, cats, girly things, keychains, money, rainy weather, the color <span style="color: pink;">pink</span><br>
                <strong>dislikes</strong> (read: most are fears): cat cruelty, frogs, humans, lizards, school, sharks, tickles
            </div>
        </div>
        <table>
            <tr>
                <th>achievements</th>
            </tr>
            <tr>
                <td>
                    <div class="decorative-line">°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°</div>
                    <div class="center-text">with honors (elementary and high school)</div>
                </td>
            </tr>
        </table>
        <table>
            <tr>
                <th>skills</th>
            </tr>
            <tr>
                <td>
                    <div class="decorative-line">°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°</div>
                    <div class="center-text">flexibility, organization, willingness to learn, writing proficiency</div>
                </td>
            </tr>
        </table>
        <table>
            <tr>
                <th>hobbies</th>
            </tr>
            <tr>
                <td>
                    <div class="decorative-line">°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°</div>
                    annoying my cat, bed rotting, cleaning my room at 3 am, reading, scrolling on pinterest, talking to myself, watching anime
                </td>
            </tr>
        </table>
        <table>
            <tr>
                <th>interests</th>
            </tr>
            <tr>
                <td>
                    <div class="decorative-line">°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°</div>
                    class suspension, fiction, ghosting people, love & peace, performing art, random cat memes and pics, twitter fights
                </td>
            </tr>
        </table>
        <table>
            <tr>
                <th>more (and most random) facts about me</th>
            </tr>
            <tr>
                <td>
                    <div class="decorative-line">°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°°❀⋆.ೃ࿔.*:･･:*.ೃ࿔.⋆❀°</div>
                    <ul>
                        <li>calls vs texts ✅ (but too lazy to type)</li>
                        <li>cant control facial expressions</li>
                        <li>color palette: <span style="color: pink;">pink</span>, black, white</li>
                        <li>dyslexic but i love reading nonetheless</li>
                        <li>favorite fruits: <span style="color: violet;">grapes</span>, <span style="color: yellow;">corn</span> (?) (grain?)</li>
                        <li>favorite jjk characters: nanami <3 choso, toji</li>
                        <li>favorite series: when we were young</li>
                        <li>i dont exactly hate my surname but i prefer using my middle name</li>
                        <li>i have motion sickness</li>
                        <li>i like dancing and i want to be better at it</li>
                        <li>i like <span style="color: red;">spicy foods</span></li>
                        <li>randomly speaks in english</li>
                        <li>short attention span</li>
                        <li>very clumsy</li>
                    </ul>
                </td>
            </tr>
        </table>
        <div class="where-to-find-me">
            <h3 onclick="toggleFindMe()">where to find me ദ്ദി(ᵔᗜᵔ)</h3>
            <div id="find-me-content" class="hidden find-me-content">
                <p><strong>email</strong> <a href="mailto:anonuevo.jana@ue.edu.ph">anonuevo.jana@ue.edu.ph</a></p>
                <p><strong>fb</strong> <a href="https://www.facebook.com/tanrangdan" target="_blank">Jana</a></p>
                <p><strong>ig</strong> <a href="https://www.instagram.com/jnflav" target="_blank">jnflav</a></p>
            </div>
        </div>
    </div>

    <script>
        function toggleFindMe() {
            const content = document.getElementById('find-me-content');
            content.classList.toggle('hidden');
        }
    </script>
</body>
</html>
