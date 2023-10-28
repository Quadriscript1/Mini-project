<template>
    <div class=" bg-dark mt-3 pb-5">
        <div class="row pb-4 ">
            <div class="col-sm-1"></div>
            <div class="col-sm-3 mt-3">
                <img src="../assets/crown.png" alt="">
            </div>
            <div class="col-sm-4">

            </div>
            <div class="col-sm-3 text-white mt-5">
                <p>We Would Love to Hear From You</p>
                <div class="mt-1 text">
                    <input type="text" placeholder="Subscription  to Newsletter ">
                    <button class="btn btn-sm btn-info"><i class="bi bi-chevron-right"></i></button>
                </div>

            </div>
            <div class="col-sm-1"></div>
        </div>
        <hr class="container" style="border: 1px solid white;width: 65rem;">

        <div class="row pb-5 mt-2">
            <div class="col-sm-1"></div>
            <div class="col-sm-4 text-white listen">
                <ul>
                    <li class="list">
                        Contact Us
                    </li>
                    <li class="list">
                        Privacy
                    </li>
                    <li class="list">
                        Terms of Use
                    </li>
                </ul>
            </div>
            <div class="col-sm-2"></div>
            <div class="col-sm-4 text-white copy">
                ©2023 Crownbirth Ltd. All Rights Reserved.
            </div>
            <div class="col-sm-1"></div>
        </div>


    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.chevron{
    color: yellow;
}
.text input {
    outline: none;
    border: 1px solid #C9D3C7;
    border-radius: 5px;
    width: 300px;
    padding: 5px 0 5px 15px;
}

.listen .list {
    list-style-type: none;
}

.listen ul {
    display: flex;
    justify-content: space-between;
    margin: 0 5px 0 6rem;
}
</style>