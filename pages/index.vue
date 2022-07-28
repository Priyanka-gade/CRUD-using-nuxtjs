<template >
  <div class="grid justify-center justify-items-center rounded w-96 p-5 m-10 bg-gradient-to-r from-cyan-200 to-blue-400">
    <h1 class="font-bold text-2xl text-red-500 ">ToDo App</h1>
    <!-- <p>Add your bucket list in todo app</p> -->
    <br/>
    <div class="border border-solid border-slate-500 bg-slate-100 rounded font-serif p-4">
      <div>
        <label>Title :</label>&nbsp;
        <input type="text" class="border border-solid border-slate-500 "/>
      </div>
      <br/>
      <div>
        <button class="float-right border border-2 border-solid bg-blue-600 rounded-lg text-white p-1 font-serif border-black hover:bg-blue-800">Add</button>
      </div>
    </div>
  </div>
</template>
<script>
    const bucketList = reactive({
        title:"ToDo1",
        edit: "Edit",
        delete:"Delete"
    });
</script>

