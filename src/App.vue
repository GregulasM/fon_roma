<script setup>

</script>

<template>


<body>
    <div class="top-bar">
        <div class="logo">
            <img src="../evernote-logo.svg" alt="Logo">
            poe.ninja
        </div>
        <div class="menu">
            <a href="#">Economy</a>
            <a href="#">Builds</a>
            <a href="#">Streamers</a>
            <a href="#">Share PoB</a>
        </div>
    </div>
</body>

</template>

<style scoped>
 html, body {
            height: 100%;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        body::before {
            content: "";
            position: fixed;
            top: -10px;
            left: -10px;
            width: calc(100% + 20px);
            height: calc(100% + 20px);
            background: url('https://img2.joyreactor.cc/pics/post/full/Path-of-Exile-wallpapers-Игры-3352206.jpeg') no-repeat center center;
            background-size: cover;
            filter: blur(0px);
            z-index: -1;
        }
        .top-bar {
            width: 100%;
            height: 50px;
            background-color: rgba(20, 20, 20, 0.9);
            color: white;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 0 20px;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
            position: fixed;
            top: 0;
            left: 0;
        }
        .top-bar .logo, .top-bar .menu {
            display: flex;
            align-items: center;
        }
        .top-bar .logo img {
            height: 30px;
            margin-right: 10px;
        }
        .top-bar .menu a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }
</style>
