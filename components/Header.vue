<template>
    <div class="header">
        <div class="navbar left">
            <ul>
                <li><NuxtLink to="/">Photography</NuxtLink></li>
                <li><NuxtLink to="/about">About</NuxtLink></li>
            </ul>
        </div>
        <div class="logo">
            <img src="~assets/watermark.png" />
        </div>
        <div class="navbar right">
            <ul>
                <li>
                    <span><img src="~assets/email.svg" /></span>
                </li>
                <li>
                    <span
                        ><NuxtLink
                            to="https://www.instagram.com/__lowkey__photography/"
                            ><img src="~assets/instagram.svg" /></NuxtLink
                    ></span>
                </li>
            </ul>
        </div>
    </div>
</template>
