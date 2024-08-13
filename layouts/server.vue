<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/">Logo</NuxtLink>
                <ul>
                    <li><NuxtLink to="console/">Console</NuxtLink></li>
                    <li><NuxtLink to="files/">Files</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <div>
            <slot />
        </div>
    </div>
</template>
