<template>
  <div id="app">
    <div class="bg-dark text-white text-center py-4 mb-4">
      <h1>Employee Management System</h1>
      <h5 class="text-secondary">CRUD Operations using Vue.js, Axios and MockAPI</h5>
    </div>

    <EmployeeForm />
    <EmployeeList />
    <UpdateEmployee />
    <DeleteEmployee />
  </div>
</template>

<script>
import EmployeeForm from './components/EmployeeForm.vue';
import EmployeeList from './components/EmployeeList.vue';
import UpdateEmployee from './components/UpdateEmployee.vue';
import DeleteEmployee from './components/DeleteEmployee.vue';

export default {
  name: 'App',
  components: {
    EmployeeForm,
    EmployeeList,
    UpdateEmployee,
    DeleteEmployee
  }
}
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  color: #2c3e50;
}
</style>