<script setup>
import { onBeforeMount, ref, toRaw } from 'vue';
import { base64url } from 'multiformats/bases/base64';
import { PlusIcon as PlusIconMini } from '@heroicons/vue/solid';
import { CheckCircleIcon, TrashIcon } from '@heroicons/vue/outline';
import { Web5 } from '@tbd54566975/web5';

// Initialize variables here

// Loading or Creating User Data
onBeforeMount(async () => {

});

// Adding ToDos
const newTodoDescription = ref('');

// Adding a ToDo
async function addTodo() {

}

// Deleting a ToDo
async function deleteTodo(todoItem) {

}

// Toggling ToDo Completion Status
async function toggleTodoComplete(todoItem) {

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
        
        <!-- Add ToDos Form -->

        <!-- ToDos -->
        
    </div>
</template>