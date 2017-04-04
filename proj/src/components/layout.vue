<template>
  <div class="wapper">
    <!-- top navbar-->
    <header>
      This is header
      <slot name="header">
        slot when is null
      </slot>
    </header>
    <!-- sidebar-->
    <aside>
      sidebar
      <slot name="sidebar">
        slot when is null
      </slot>
    </aside>
    <!-- offsidebar-->
    <aside>
      offsidebar
      <slot name="offsidebar">
        slot when is null
      </slot>
    </aside>
    <!-- Main section-->
    <section>
      Main Content
      <slot name="main">
        slot when is null
      </slot>
    </section>
    <!-- Page footer-->
    <footer>
       <span>&copy; 2017 - Angle</span>
       <slot name="footer">
        slot when is null
       </slot>
    </footer>
  </div>

</template>

<script>
export default {

}
</script>

<style>

</style>
