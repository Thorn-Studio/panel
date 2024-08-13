<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/">Logo</NuxtLink>
                <ul>
                    <li><NuxtLink to="/servers/">Servers</NuxtLink></li>
                    <li><NuxtLink to="/settings/">Settings</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <div>
            <slot />
        </div>
    </div>
</template>
