<template>
  <div>
  <span className="timestamp">{{ timestamp }}</span>
</div>
  </template>
  
  <script>
  export default {
    props: {
        timestamp: String,
    },
  };
  </script>