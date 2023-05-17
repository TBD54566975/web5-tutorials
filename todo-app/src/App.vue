<script setup>
import { onBeforeMount, ref, toRaw } from 'vue';
import { PlusIcon as PlusIconMini } from '@heroicons/vue/solid';
import { CheckCircleIcon, TrashIcon } from '@heroicons/vue/outline';
import { Web5 } from '@tbd54566975/web5';

onBeforeMount(async () => {

  // Populate todos from DWN

  // Add entry to Todo array

});

// Adding Todos

async function addTodo() {

  // Create the record in DWN

  // add DWeb message recordId as a way to reference the message for further operations
  // e.g. updating it or overwriting it

}

// Delete todo
async function deleteTodo(todoItem) {

  // Delete the record in DWN

}

// Set a todo as complete/incomplete
async function toggleTodoComplete(todoItem) {

  // Get record in DWN

  // Update the record in DWN

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