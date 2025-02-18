---
layout: about
title: About
comments: true
order: 8
---

<html lang="en">
<head>
    <style>
        /* body {
            font-family: 'Verdana', sans-serif;
            background-color: #f5f5f5;
            color: #444;
            margin: 0;
            padding: 0;
            line-height: 1.8;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            background: #fff;
            padding: 20px 30px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        } */
        h1 {
            color: #148f77;
            font-size: 2.5em;
            margin-bottom: 10px;
            text-align: center;
        }
        h2 {
            color: #148f77;
            font-size: 1.5em;
            margin: 20px 0 10px;
        }
        p {
            margin: 10px 0;
            text-align: justify;
        }
        .highlight {
            color: #991f05;
            font-weight: bold;
            display: block;
            text-align: center;
            margin: 10px 0 20px;
            font-size: 1.1em;
        }
        .content-section {
            margin-bottom: 20px;
        }
        .image-container {
            text-align: center;
            margin: 20px 0;
        }
        .image-container img {
            max-width: 100%;
            border-radius: 5px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }
        .cta {
            text-align: center;
            margin-top: 30px;
            font-size: 1.2em;
            color: #148f77;
            font-weight: bold;
        }
        footer {
            text-align: center;
            font-size: 0.9em;
            color: #888;
            margin-top: 40px;
        }
        form {
            display:flex;
            flex-direction:column;
            align-items:normal;
            gap:15px;
        }
        input:not([type="submit"]), label textarea{
            display:block;
            width:100%;
            padding-left:10px; 
            /* outline:none; */
        }
        textarea {
            padding-top:10px; 
        }
        input[type="submit"] {
            width:200px;
            height:3em;
            margin: 0 auto;
            border: 2px solid #1A1A1A;
            border-radius: 15px;
            color: #FFFFFF;
            background-color: #000000;
            cursor: pointer;
            box-sizing: border-box;
            text-decoration: none;
            transition: all 300ms cubic-bezier(.23, 1, 0.32, 1);
            user-select: none;
            -webkit-user-select: none;
            touch-action: manipulation;
            will-change: transform;
            min-height: 60px;
            text-align: center;
        }
        input[type="submit"]:focus {
            outline-color: grey;
            outline-width:2px;
            border:5px solid white;
        }
        input[type="submit"]:disabled {
            pointer-events: none;
        }
        input[type="submit"]:hover,input[type="submit"]:active {
            box-shadow: rgba(0, 0, 0, 0.25) 0 8px 15px;
            transform: translateY(-2px);
        }
        input[type="submit"]:active {
            box-shadow: none;
        transform: translateY(0);
        }

    </style>
    <title>Who</title>
</head>
<body>
    <div class="container">
        <h1>Hello, World!</h1>

        <div class="content-section">
            <p>Hi I'm Johnson and I'm starting on this path of 
            becoming a full stack software engineer. I am interested in 
            building applications that help others. I like solving problems 
            that I encounter and sharing the process I took to overcome those obstacles. 
            It's also a pleasure to hear experiences of other's facing or have faced similar problems, 
            I learn a lot from their experiences as well as from reflecting on mine.
            <br>
            Resting and knowing how to cope with stress is also important. 
            I like to listen to music and read to find peace. This year I'm starting 
            this blog as a side activity, for the future me and readers. I'll share my experience 
            along the way. Thanks for reading and hope you achieve your goals too!</p>
        </div>

        <h2 style="text-decoration:underline">Contact Form:</h2>

        <form action="https://api.web3forms.com/submit" method="POST">

        <!-- Public Key Area-->
        <input type="hidden" name="access_key" value="a774a0ec-d91c-4dc2-92ae-36eb81180af8">

        <!-- Form Inputs. Each input must have a name="" attribute -->
        <label for="name">Name: <input id="name" type="text" name="name" placeholder="Name/Subject" required></label>
        <label for="email">Email: <input id="email" type="email" name="email" placeholder="e.g. example.gmail.com" required></label>
        <label for="msg">Message: <textarea id="msg" name="message" placeholder="Type your message here" required></textarea></label>

        <!-- Honeypot Spam Protection -->
        <input type="checkbox" name="botcheck" class="hidden" style="display: none;">

        <!-- Custom Confirmation / Success Page -->
        <!-- <input type="hidden" name="redirect" value="https://mywebsite.com/thanks.html"> -->

        <input type="submit" value="Submit Form">

    </form>



    </div>
</body>
</html>
