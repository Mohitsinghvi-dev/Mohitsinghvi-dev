- 👋 Hi, I’m @Mohitsinghvi-dev
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Mohitsinghvi-dev/Mohitsinghvi-dev is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---><!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> NAV BAR USING FLEX PROPERTY</title>


    <style>
        .logo {
            /* background-color: aqua; */
            height: 23px;
            width: 45px;
        }

        .logo img {
            width: 132px;
        
        }

        .rightbar ul {
            display: flex;
            gap: 34px;
        }

        .rightbar ul li {
            list-style: none;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            font-family: cursive;
            background-color:white;
            height: 15vh;    
        }
        body{
            background-color: grey;
        }
    </style>

</head>

<body>
    <header>
        <nav>
            <div class="logo">
                <img src="https://www.ultraedit.com/wp-content/uploads/2023/01/UE-Logo-1.webp" alt="">
            </div>
            <div class="rightbar">
                <ul>
                    <li> <span> products </span> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="14"
                            height="14" color="#000000" fill="none">
                            <path d="M18 9.00005C18 9.00005 13.5811 15 12 15C10.4188 15 6 9 6 9" stroke="currentColor"
                                stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                        </svg></li>
                    <li><span> pricing </span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="14"
                            height="14" color="#000000" fill="none">
                            <path d="M18 9.00005C18 9.00005 13.5811 15 12 15C10.4188 15 6 9 6 9" stroke="currentColor"
                                stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                        </svg></li>
                    <li> <span>resources</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="14"
                            height="14" color="#000000" fill="none">
                            <path d="M18 9.00005C18 9.00005 13.5811 15 12 15C10.4188 15 6 9 6 9" stroke="currentColor"
                                stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                        </svg></li>
                    <li><span> About us</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="14"
                            height="14" color="#000000" fill="none">
                            <path d="M18 9.00005C18 9.00005 13.5811 15 12 15C10.4188 15 6 9 6 9" stroke="currentColor"
                                stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                        </svg> </li>
                </ul>
            </div>
        </nav>
    </header>
</body>

</html>
