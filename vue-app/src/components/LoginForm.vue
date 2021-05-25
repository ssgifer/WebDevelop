<template>
<div class = "container">
    <div class = "row mt-">
        <div class = "col-sm-4">
            <form>
                <div class = "form-group">
                    <label for = "username">User Name</label>
                    <input type = "text" class = "form-control" id = "username" name = "username" />
                </div>
                <div class = "form-group">
                    <label for = "password">Password</label>
                    <input type = "text" class = "form-control" id = "password" name = "password" />
                </div>
                <button type = "submit" class = "btnlogin">Login</button>
            </form>
        </div>
    </div>    
</div>
</template>

<script>
export default {
    name : "LoginForm",
    data() {
        return{};
    }
};
</script>
<style>
</script>