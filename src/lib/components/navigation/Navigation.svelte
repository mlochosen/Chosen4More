<script>

import { goto } from "$app/navigation";

</script>
<nav>
<div class="navbar bg-blue-700 shadow-sm">
  <div class="navbar-start">
    <div class="dropdown">
      <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
        <svg aria-label="Menu" xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /> </svg>
      </div>
      <ul
        tabindex="-1"
        class="menu menu-sm dropdown-content bg-base-100 rounded-box z-1 mt-3 w-52 p-2 shadow">
        <li><a>Item 1</a></li>
        <li>
          <a>Parent</a>
          <ul class="p-2">
            <li><a>Submenu 1</a></li>
            <li><a>Submenu 2</a></li>
          </ul>
        </li>
        <li><a>Item 3</a></li>
      </ul>
    </div>
    <a class="btn btn-ghost text-xl">Chosen For More</a>
  </div>
  <div class="navbar-center hidden lg:flex">
    <ul class="menu menu-horizontal px-1">
       <li>
        <details>
          <summary>The Heart Behind It</summary>
          <ul class="p-2 bg-base-100 w-40 z-1">
            <li><a>Mission & Values</a></li>
            <li><a>Our Why</a></li>
          </ul>
        </details>
      </li>
      <li>
        <details>
          <summary>Program & Services</summary>
          <ul class="p-2 bg-base-100 w-40 z-1">
            <li><a>Rise Up</a></li>
            <li><a>More in Motion</a></li>
            <li><a>Lead the Way</a></li>
            <li><a>Next Stop: More (Field Trips)</a></li>
            <li><a>Summer Camp</a></li>
            <li><a>More Academy (Homeschool)</a></li>
          </ul>
        </details>
      </li>
       <li>
        <details>
          <summary>Be The Impact</summary>
          <ul class="p-2 bg-base-100 w-40 z-1">
            <li><a>Employment Opportunities</a></li>
            <li><a>Volunteer Opportunities</a></li>
            <li><a>Internships</a></li>
          </ul>
        </details>
      </li>
    <li><a>Donate</a></li>
      <li><a>Contact Us</a></li>
    </ul>
  </div>
  <div class="navbar-end">
    <div class="justify-between">
      <a class="btn bg-white text-yellow-600 hover:bg-yellow-300" on:click={()=> goto('item_shop')}>Store</a>
  </div>
</div>
  </div>
  </nav>