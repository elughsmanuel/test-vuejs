<template>
    <div class="heading-main">
      <h4>
        <slot name="heading-main"></slot>
      </h4>
    </div>
</template>
  
  <style>
  @media (min-width: 1024px) {
    .heading-main {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }
  }
  </style>
  