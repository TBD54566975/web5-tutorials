<script setup>
import { onBeforeMount, onMounted, ref, toRaw } from 'vue';
import { base64url } from 'multiformats/bases/base64';
import { PlusIcon as PlusIconMini } from '@heroicons/vue/solid';
import { CheckCircleIcon, TrashIcon } from '@heroicons/vue/outline';
import { Web5 } from '@tbd54566975/web5';


// Loading or Creating User Data
onBeforeMount(async () => {
    // Displaying Todos

    // Populate Todos from DWN

    // Serialize Todo
});

// Adding Todos
const newTodoDescription = ref('');

async function addTodo() {

}

// Deleting Todos
async function deleteTodo(todoRecordId) {

}

// Toggling Todo Status
async function toggleTodoComplete(todoRecordId) {

}

</script>

<template>
    <div class="flex flex-col items-center justify-center min-h-full px-8 py-12 sm:px-6">
        <!-- Title -->
        <div class="sm:max-w-md sm:w-full">
            <h2 class="font-bold text-3xl text-center tracking-tight">
                Todo List
            </h2>
        </div>
        
        <!-- Add Todo Form -->

        <!-- Todos -->
        
    </div>
</template>