<template>
  <div>
     <h3> Student Form </h3>
     <form>
         <p>
            <label>Name: </label>
            <input type="text" name="txtStudentName"/>
         </p>
         <p>
            <label>Class: </label>
            <input type="text" name="txtStudentClass"/>
         </p>
         <p>
            <label>Mobile No: </label>
            <input type="text" name="txtStudentMobile"/>
         </p>
         <p>
           <button>Submit</button>
         </p>
     </form>
  </div>
</template>

<script>

export default {
  data () {
    return {

    }
  }
}
</script>
