<script>
var address = document.reg_form.address;
var gender = document.reg_form.gender;
if (address.value.length <= 0) {
    alert("Address is required");
    address.focus();
    return false;
    }
if (gender.value.length <= 0) {
    alert("Gender is required");
    gender.focus();
    return false;
            }
</script>