<template>
   <div class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0">
     <Sidebar/>
     <h1>This is Home Page</h1>
   </div>
 </template>
 
 <script>
 import Sidebar from './Sidebar';
 export default {
   name: 'HomePage',
   components: {
     Sidebar,
   },
 }
 </script>
 