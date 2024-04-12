<template>
    <footer class="pt-20 bg-gray-100 dark:bg-body border-t border-gray-200 dark:border-gray-100/20">
        <AtomsContainer class-name="pb-10">
            <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-8 gap-y-10">
                <div class="col-span-2 md:col-span-4 lg:col-span-2">
                    <NuxtLink to="/" class=" flex items-center gap-2">
                        <span class="flex">
                            <span class="w-3 h-6 rounded-l-full flex bg-[#b81414]"></span>
                            <span class="w-3 h-6 rounded-r-full flex bg-[#b81414] mt-2"></span>
                        </span>
                        <span class="text-xl font-bold text-gray-700 dark:text-white">Rubie</span>
                    </NuxtLink>

                    <p class="text-gray-600 dark:text-gray-300 pt-6">
                        Transforme sua visão em realidade digital!                    </p>
                </div>
            </div>
        </AtomsContainer>
        <div class="py-2 bg-gray-200 dark:bg-[rgb(10,16,29)]">
            <AtomsContainer>
                <div class="flex justify-between items-center gap-5 text-gray-600 dark:text-gray-300">
                    <div class="">
                        &copy; {{ new Date().getFullYear() }} Todos os direitos reservados.
                    </div>

                    <div class="flex items-center gap-x-3">


                       
                    </div>
                </div>
            </AtomsContainer>
        </div>
    </footer>
</template>

<script lang="ts" setup>
const quickLinks = [
    {
        href: "#",
        text: "About us"
    },
    {
        href: "#",
        text: "News"
    },
    {
        href: "#",
        text: "Team"
    },
    {
        href: "#",
        text: "Solution"
    }
]
const ressourcesLinks = [
    {
        href: "#",
        text: "Developpers"
    },
    {
        href: "#",
        text: "Integration"
    },
    {
        href: "#",
        text: "Pricing"
    }
]

const supportLinks = [
    {
        href: "#",
        text: "Contact-us"
    },
    {
        href: "#",
        text: "Licence"
    },
    {
        href: "#",
        text: "Terms"
    },
    {
        href: "#",
        text: "FAQ"
    }
]


</script>