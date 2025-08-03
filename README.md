<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   EduForge – IT Notes &amp; Tutorials Platform
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
      font-family: 'Inter', sans-serif;
    }
  </style>
 </head>
 <body class="bg-gray-50 text-gray-900 min-h-screen flex flex-col">
  <!-- Header / Navbar -->
  <header class="bg-white shadow sticky top-0 z-50">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-16">
     <a class="flex items-center space-x-2" href="#">
      <img alt="EduForge logo, stylized letters E and F in green and blue" class="h-10 w-10 rounded" height="40" src="https://storage.googleapis.com/a1aa/image/d88b487a-f7fd-4dba-30bd-30f0836f68a2.jpg" width="40"/>
      <span class="font-bold text-xl text-green-700">
       EduForge
      </span>
     </a>
     <nav class="hidden md:flex space-x-8 font-semibold text-gray-700">
      <a class="hover:text-green-700 transition" href="#home">
       Home
      </a>
      <a class="hover:text-green-700 transition" href="#bsc-it">
       BSc IT
      </a>
      <a class="hover:text-green-700 transition" href="#msc-it">
       MSc IT
      </a>
      <a class="hover:text-green-700 transition" href="#notes">
       Notes
      </a>
      <a class="hover:text-green-700 transition" href="#tutorials">
       Tutorials
      </a>
      <a class="hover:text-green-700 transition" href="#search">
       Search
      </a>
     </nav>
     <button aria-label="Open menu" class="md:hidden text-gray-700 hover:text-green-700 focus:outline-none focus:ring-2 focus:ring-green-700" id="mobile-menu-button">
      <i class="fas fa-bars fa-lg">
      </i>
     </button>
    </div>
   </div>
   <!-- Mobile menu -->
   <nav aria-label="Mobile menu" class="hidden md:hidden bg-white border-t border-gray-200" id="mobile-menu">
    <a class="block px-4 py-3 border-b border-gray-200 hover:bg-green-50" href="#home">
     Home
    </a>
    <a class="block px-4 py-3 border-b border-gray-200 hover:bg-green-50" href="#bsc-it">
     BSc IT
    </a>
    <a class="block px-4 py-3 border-b border-gray-200 hover:bg-green-50" href="#msc-it">
     MSc IT
    </a>
    <a class="block px-4 py-3 border-b border-gray-200 hover:bg-green-50" href="#notes">
     Notes
    </a>
    <a class="block px-4 py-3 border-b border-gray-200 hover:bg-green-50" href="#tutorials">
     Tutorials
    </a>
    <a class="block px-4 py-3 hover:bg-green-50" href="#search">
     Search
    </a>
   </nav>
  </header>
  <main class="flex-grow max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8">
   <!-- Hero Section -->
   <section class="text-center max-w-4xl mx-auto mb-16" id="home">
    <h1 class="text-4xl sm:text-5xl font-extrabold text-green-700 mb-4">
     EduForge
    </h1>
    <p class="text-lg sm:text-xl text-gray-700 mb-6">
     Your ultimate platform for
     <span class="font-semibold">
      BSc IT
     </span>
     and
     <span class="font-semibold">
      MSc IT
     </span>
     notes and tutorials.
    </p>
    <p class="text-gray-600 max-w-2xl mx-auto mb-8">
     Access well-structured notes, watch handpicked YouTube tutorials, and enhance your learning experience with EduForge.
    </p>
    <a class="inline-block bg-green-700 text-white px-6 py-3 rounded-md font-semibold shadow hover:bg-green-800 transition" href="#bsc-it">
     Explore BSc IT Notes
    </a>
   </section>
   <!-- Quick Semester Navigation -->
   <section aria-label="Quick semester navigation" class="mb-16">
    <h2 class="text-2xl font-bold text-gray-800 mb-6 text-center">
     Quick Semester Navigation
    </h2>
    <div class="flex flex-wrap justify-center gap-4">
     <!-- BSc IT Semesters -->
     <a class="bg-green-100 text-green-800 px-4 py-2 rounded-md font-semibold shadow hover:bg-green-200 transition min-w-[80px] text-center" href="#bsc-sem1">
      BSc Sem 1
     </a>
     <a class="bg-green-100 text-green-800 px-4 py-2 rounded-md font-semibold shadow hover:bg-green-200 transition min-w-[80px] text-center" href="#bsc-sem2">
      BSc Sem 2
     </a>
     <a class="bg-green-100 text-green-800 px-4 py-2 rounded-md font-semibold shadow hover:bg-green-200 transition min-w-[80px] text-center" href="#bsc-sem3">
      BSc Sem 3
     </a>
     <a class="bg-green-100 text-green-800 px-4 py-2 rounded-md font-semibold shadow hover:bg-green-200 transition min-w-[80px] text-center" href="#bsc-sem4">
      BSc Sem 4
     </a>
     <a class="bg-green-100 text-green-800 px-4 py-2 rounded-md font-semibold shadow hover:bg-green-200 transition min-w-[80px] text-center" href="#bsc-sem5">
      BSc Sem 5
     </a>
     <a class="bg-green-100 text-green-800 px-4 py-2 rounded-md font-semibold shadow hover:bg-green-200 transition min-w-[80px] text-center" href="#bsc-sem6">
      BSc Sem 6
     </a>
     <!-- MSc IT Semesters -->
     <a class="bg-blue-100 text-blue-800 px-4 py-2 rounded-md font-semibold shadow hover:bg-blue-200 transition min-w-[80px] text-center" href="#msc-sem1">
      MSc Sem 1
     </a>
     <a class="bg-blue-100 text-blue-800 px-4 py-2 rounded-md font-semibold shadow hover:bg-blue-200 transition min-w-[80px] text-center" href="#msc-sem2">
      MSc Sem 2
     </a>
     <a class="bg-blue-100 text-blue-800 px-4 py-2 rounded-md font-semibold shadow hover:bg-blue-200 transition min-w-[80px] text-center" href="#msc-sem3">
      MSc Sem 3
     </a>
     <a class="bg-blue-100 text-blue-800 px-4 py-2 rounded-md font-semibold shadow hover:bg-blue-200 transition min-w-[80px] text-center" href="#msc-sem4">
      MSc Sem 4
     </a>
    </div>
   </section>
   <!-- Recent Uploads / Trending Subjects -->
   <section aria-label="Recent uploads and trending subjects" class="mb-16 max-w-5xl mx-auto">
    <h2 class="text-2xl font-bold text-gray-800 mb-6 text-center">
     Recent Uploads &amp; Trending Subjects
    </h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8">
     <!-- Card 1 -->
     <article class="bg-white rounded-lg shadow p-5 flex flex-col">
      <img alt="Cover image showing a digital illustration of computer fundamentals with circuit board and computer icons" class="rounded-md mb-4 object-cover h-40 w-full" height="200" src="https://storage.googleapis.com/a1aa/image/02e7ddbe-f252-4cb1-4a80-9f4bf0a4d280.jpg" width="400"/>
      <h3 class="text-lg font-semibold text-green-700 mb-2">
       Computer Fundamentals - BSc Sem 1
      </h3>
      <p class="text-gray-600 flex-grow">
       Comprehensive notes covering basics of computer hardware, software, and architecture.
      </p>
      <a class="mt-4 inline-block text-green-700 font-semibold hover:underline" href="#bsc-sem1">
       View Notes &amp; Tutorials
      </a>
     </article>
     <!-- Card 2 -->
     <article class="bg-white rounded-lg shadow p-5 flex flex-col">
      <img alt="Illustration of data structures with nodes and linked lists in a digital style" class="rounded-md mb-4 object-cover h-40 w-full" height="200" src="https://storage.googleapis.com/a1aa/image/5679c21a-3dde-4783-31fb-e3a14be2a458.jpg" width="400"/>
      <h3 class="text-lg font-semibold text-green-700 mb-2">
       Data Structures - BSc Sem 3
      </h3>
      <p class="text-gray-600 flex-grow">
       Detailed notes and video tutorials on arrays, linked lists, stacks, queues, and trees.
      </p>
      <a class="mt-4 inline-block text-green-700 font-semibold hover:underline" href="#bsc-sem3">
       View Notes &amp; Tutorials
      </a>
     </article>
     <!-- Card 3 -->
     <article class="bg-white rounded-lg shadow p-5 flex flex-col">
      <img alt="Abstract digital art representing advanced algorithms with flowcharts and code snippets" class="rounded-md mb-4 object-cover h-40 w-full" height="200" src="https://storage.googleapis.com/a1aa/image/dff6c2a2-413a-4e68-9773-b1dd30e34015.jpg" width="400"/>
      <h3 class="text-lg font-semibold text-blue-700 mb-2">
       Advanced Algorithms - MSc Sem 2
      </h3>
      <p class="text-gray-600 flex-grow">
       In-depth notes and tutorials on graph algorithms, dynamic programming, and complexity analysis.
      </p>
      <a class="mt-4 inline-block text-blue-700 font-semibold hover:underline" href="#msc-sem2">
       View Notes &amp; Tutorials
      </a>
     </article>
    </div>
   </section>
   <!-- Notes Page (per subject) -->
   <section class="mb-16 max-w-6xl mx-auto" id="notes">
    <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">
     Notes by Subject &amp; Semester
    </h2>
    <!-- BSc IT Semester 1 -->
    <article class="mb-12" id="bsc-sem1">
     <h3 class="text-2xl font-semibold text-green-700 mb-6 border-b border-green-300 pb-2">
      BSc IT - Semester 1
     </h3>
     <!-- Subject: Computer Fundamentals -->
     <section class="mb-10">
      <h4 class="text-xl font-semibold text-gray-800 mb-4">
       Subject: Computer Fundamentals
      </h4>
      <!-- Topic 1 -->
      <div class="bg-white rounded-lg shadow p-6 mb-6">
       <h5 class="text-lg font-semibold text-green-700 mb-2">
        Topic 1: What is Computer?
       </h5>
       <div class="prose max-w-none text-gray-700 mb-4">
        <p>
         A computer is an electronic device that manipulates information or data. It has the ability to store,
                retrieve, and process data.
        </p>
        <p>
         Computers are used in various fields such as education, business, healthcare, and entertainment.
        </p>
       </div>
       <a class="inline-flex items-center text-green-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=O5nskjZ_GoI" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch YouTube Tutorial
       </a>
      </div>
      <!-- Topic 2 -->
      <div class="bg-white rounded-lg shadow p-6 mb-6">
       <h5 class="text-lg font-semibold text-green-700 mb-2">
        Topic 2: Computer Components
       </h5>
       <div class="prose max-w-none text-gray-700 mb-4">
        <p>
         The main components of a computer include the Central Processing Unit (CPU), memory, input/output devices,
                and storage.
        </p>
        <p>
         Understanding these components is essential for grasping how computers operate.
        </p>
       </div>
       <a class="inline-flex items-center text-green-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=8Nq3bq3Q6xk" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch YouTube Tutorial
       </a>
      </div>
     </section>
     <!-- Subject: Programming Basics -->
     <section>
      <h4 class="text-xl font-semibold text-gray-800 mb-4">
       Subject: Programming Basics
      </h4>
      <!-- Topic 1 -->
      <div class="bg-white rounded-lg shadow p-6 mb-6">
       <h5 class="text-lg font-semibold text-green-700 mb-2">
        Topic 1: Introduction to Programming
       </h5>
       <div class="prose max-w-none text-gray-700 mb-4">
        <p>
         Programming is the process of creating instructions for computers to perform specific tasks.
        </p>
        <p>
         This topic covers basic programming concepts and languages.
        </p>
       </div>
       <a class="inline-flex items-center text-green-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=8mAITcNt710" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch YouTube Tutorial
       </a>
      </div>
      <!-- Topic 2 -->
      <div class="bg-white rounded-lg shadow p-6 mb-6">
       <h5 class="text-lg font-semibold text-green-700 mb-2">
        Topic 2: Variables and Data Types
       </h5>
       <div class="prose max-w-none text-gray-700 mb-4">
        <p>
         Variables store data values, and data types define the kind of data a variable can hold.
        </p>
        <p>
         This topic explains different data types and how to use variables in programming.
        </p>
       </div>
       <a class="inline-flex items-center text-green-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=Z1Yd7upQsXY" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch YouTube Tutorial
       </a>
      </div>
     </section>
    </article>
    <!-- BSc IT Semester 3 -->
    <article class="mb-12" id="bsc-sem3">
     <h3 class="text-2xl font-semibold text-green-700 mb-6 border-b border-green-300 pb-2">
      BSc IT - Semester 3
     </h3>
     <!-- Subject: Data Structures -->
     <section>
      <h4 class="text-xl font-semibold text-gray-800 mb-4">
       Subject: Data Structures
      </h4>
      <!-- Topic 1 -->
      <div class="bg-white rounded-lg shadow p-6 mb-6">
       <h5 class="text-lg font-semibold text-green-700 mb-2">
        Topic 1: Arrays
       </h5>
       <div class="prose max-w-none text-gray-700 mb-4">
        <p>
         Arrays are collections of elements identified by index or key, used to store multiple values in a single variable.
        </p>
       </div>
       <a class="inline-flex items-center text-green-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=6iF8Xb7Z3wQ" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch YouTube Tutorial
       </a>
      </div>
      <!-- Topic 2 -->
      <div class="bg-white rounded-lg shadow p-6 mb-6">
       <h5 class="text-lg font-semibold text-green-700 mb-2">
        Topic 2: Linked Lists
       </h5>
       <div class="prose max-w-none text-gray-700 mb-4">
        <p>
         Linked lists are linear data structures where each element points to the next, allowing efficient insertion and deletion.
        </p>
       </div>
       <a class="inline-flex items-center text-green-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=njTh_OwMljA" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch YouTube Tutorial
       </a>
      </div>
      <!-- Topic 3 -->
      <div class="bg-white rounded-lg shadow p-6 mb-6">
       <h5 class="text-lg font-semibold text-green-700 mb-2">
        Topic 3: Stacks and Queues
       </h5>
       <div class="prose max-w-none text-gray-700 mb-4">
        <p>
         Stacks and queues are abstract data types that follow specific orderings for adding and removing elements.
        </p>
       </div>
       <a class="inline-flex items-center text-green-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=wjI1WNcIntg" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch YouTube Tutorial
       </a>
      </div>
     </section>
    </article>
    <!-- MSc IT Semester 2 -->
    <article class="mb-12" id="msc-sem2">
     <h3 class="text-2xl font-semibold text-blue-700 mb-6 border-b border-blue-300 pb-2">
      MSc IT - Semester 2
     </h3>
     <!-- Subject: Advanced Algorithms -->
     <section>
      <h4 class="text-xl font-semibold text-gray-800 mb-4">
       Subject: Advanced Algorithms
      </h4>
      <!-- Topic 1 -->
      <div class="bg-white rounded-lg shadow p-6 mb-6">
       <h5 class="text-lg font-semibold text-blue-700 mb-2">
        Topic 1: Graph Algorithms
       </h5>
       <div class="prose max-w-none text-gray-700 mb-4">
        <p>
         Graph algorithms include traversal, shortest path, and connectivity algorithms used in network analysis.
        </p>
       </div>
       <a class="inline-flex items-center text-blue-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=09_LlHjoEiY" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch YouTube Tutorial
       </a>
      </div>
      <!-- Topic 2 -->
      <div class="bg-white rounded-lg shadow p-6 mb-6">
       <h5 class="text-lg font-semibold text-blue-700 mb-2">
        Topic 2: Dynamic Programming
       </h5>
       <div class="prose max-w-none text-gray-700 mb-4">
        <p>
         Dynamic programming is a method for solving complex problems by breaking them down into simpler subproblems.
        </p>
       </div>
       <a class="inline-flex items-center text-blue-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=oBt53YbR9Kk" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch YouTube Tutorial
       </a>
      </div>
      <!-- Topic 3 -->
      <div class="bg-white rounded-lg shadow p-6 mb-6">
       <h5 class="text-lg font-semibold text-blue-700 mb-2">
        Topic 3: Complexity Analysis
       </h5>
       <div class="prose max-w-none text-gray-700 mb-4">
        <p>
         Complexity analysis helps evaluate the efficiency of algorithms in terms of time and space.
        </p>
       </div>
       <a class="inline-flex items-center text-blue-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=V6mKVRU1evU" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch YouTube Tutorial
       </a>
      </div>
     </section>
    </article>
   </section>
   <!-- Search & Filter Section -->
   <section class="mb-16 max-w-4xl mx-auto" id="search">
    <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">
     Search &amp; Filter Topics
    </h2>
    <form class="bg-white rounded-lg shadow p-6 flex flex-col sm:flex-row gap-4 items-center">
     <input aria-label="Search by topic or subject" class="flex-grow border border-gray-300 rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-green-700 focus:border-transparent" id="search-input" name="search" placeholder="Search by topic or subject" type="search"/>
     <select aria-label="Filter by semester" class="border border-gray-300 rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-green-700 focus:border-transparent" id="filter-semester" name="semester">
      <option value="">
       All Semesters
      </option>
      <optgroup label="BSc IT">
       <option value="bsc-sem1">
        BSc Sem 1
       </option>
       <option value="bsc-sem2">
        BSc Sem 2
       </option>
       <option value="bsc-sem3">
        BSc Sem 3
       </option>
       <option value="bsc-sem4">
        BSc Sem 4
       </option>
       <option value="bsc-sem5">
        BSc Sem 5
       </option>
       <option value="bsc-sem6">
        BSc Sem 6
       </option>
      </optgroup>
      <optgroup label="MSc IT">
       <option value="msc-sem1">
        MSc Sem 1
       </option>
       <option value="msc-sem2">
        MSc Sem 2
       </option>
       <option value="msc-sem3">
        MSc Sem 3
       </option>
       <option value="msc-sem4">
        MSc Sem 4
       </option>
      </optgroup>
     </select>
     <button aria-label="Search topics" class="bg-green-700 text-white px-6 py-2 rounded-md font-semibold hover:bg-green-800 transition" type="submit">
      Search
     </button>
    </form>
    <p class="mt-4 text-center text-gray-600 italic">
     * Search and filter functionality to be implemented in backend or frontend framework.
    </p>
   </section>
   <!-- Tutorials Section -->
   <section class="mb-16 max-w-6xl mx-auto" id="tutorials">
    <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">
     Featured YouTube Tutorials
    </h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
     <!-- Tutorial 1 -->
     <article class="bg-white rounded-lg shadow overflow-hidden flex flex-col">
      <img alt="YouTube tutorial thumbnail showing a computer with digital icons and text 'What is Computer?'" class="w-full object-cover h-48" height="340" src="https://storage.googleapis.com/a1aa/image/1362b806-775b-4604-77bb-9ecf98d480db.jpg" width="600"/>
      <div class="p-4 flex flex-col flex-grow">
       <h3 class="text-lg font-semibold text-green-700 mb-2">
        What is Computer?
       </h3>
       <p class="text-gray-700 flex-grow mb-4">
        An introductory tutorial explaining the basics of computers, their components, and functions.
       </p>
       <a class="inline-flex items-center text-green-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=O5nskjZ_GoI" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch on YouTube
       </a>
      </div>
     </article>
     <!-- Tutorial 2 -->
     <article class="bg-white rounded-lg shadow overflow-hidden flex flex-col">
      <img alt="YouTube tutorial thumbnail showing nodes and linked lists diagram with text 'Data Structures'" class="w-full object-cover h-48" height="340" src="https://storage.googleapis.com/a1aa/image/a1b6d389-9b6f-4364-a496-7176a543bfc8.jpg" width="600"/>
      <div class="p-4 flex flex-col flex-grow">
       <h3 class="text-lg font-semibold text-green-700 mb-2">
        Data Structures Basics
       </h3>
       <p class="text-gray-700 flex-grow mb-4">
        Learn about arrays, linked lists, stacks, and queues with clear explanations and examples.
       </p>
       <a class="inline-flex items-center text-green-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=6iF8Xb7Z3wQ" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch on YouTube
       </a>
      </div>
     </article>
     <!-- Tutorial 3 -->
     <article class="bg-white rounded-lg shadow overflow-hidden flex flex-col">
      <img alt="YouTube tutorial thumbnail showing flowcharts and code snippets with text 'Advanced Algorithms'" class="w-full object-cover h-48" height="340" src="https://storage.googleapis.com/a1aa/image/098c7964-069d-4ee4-aed1-c0af0e7d875f.jpg" width="600"/>
      <div class="p-4 flex flex-col flex-grow">
       <h3 class="text-lg font-semibold text-blue-700 mb-2">
        Advanced Algorithms
       </h3>
       <p class="text-gray-700 flex-grow mb-4">
        Explore graph algorithms, dynamic programming, and complexity analysis in this detailed tutorial.
       </p>
       <a class="inline-flex items-center text-blue-700 font-semibold hover:underline" href="https://www.youtube.com/watch?v=09_LlHjoEiY" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-youtube fa-lg mr-2">
        </i>
        Watch on YouTube
       </a>
      </div>
     </article>
    </div>
   </section>
  </main>
  <!-- Footer -->
  <footer class="bg-white border-t border-gray-200 py-8 mt-auto">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-gray-600 text-sm">
    <p>
     © 2024 EduForge. All rights reserved.
    </p>
    <p class="mt-2">
     Developed for
     <span class="font-semibold">
      Arshu Malik
     </span>
     | Educational Web Platform for BSc IT &amp; MSc IT
    </p>
   </div>
  </footer>
  <script>
   const mobileMenuButton = document.getElementById('mobile-menu-button');
    const mobileMenu = document.getElementById('mobile-menu');

    mobileMenuButton.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });
  </script>
 </body>
</html>
