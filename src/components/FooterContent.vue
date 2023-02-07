<script setup>
    import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
    <div class="container-fluid text-center">
        <div class="row">
            <!-- Text -->
            <div class="col-6 col-md-6 " style="margin: auto;">
                <div class="d-flex justify-content-center flex-row bd-highlight">
                    <div class="mr-5 bd-highlight"> <a href="https://github.com/lanunezofx" target="_blank"> <img src="..\assets\img\github.png" class="img-thumbnail bg-transparent thumbnail" alt="Github Logo"  style="width:100%; max-height:50px;"></a></div>

                    <div class="mr-5 bd-highlight"> <a href="https://www.linkedin.com/in/la-nuñez/" target="_blank"> <img src="..\assets\img\linkedin.png" class="img-thumbnail bg-transparent thumbnail" alt="Linkedin Logo" style="width:100%; max-height:50px;"></a></div>

                    <div class="mr-5 bd-highlight"> <a href="https://www.youtube.com/channel/UCWDaL_ClB-hyOS5WAtzPKvg/" target="_blank"> <img src="..\assets\img\youtube.png" class="img-thumbnail bg-transparent thumbnail" alt="Youtube Logo" style="width:100%; max-height:50px;"></a></div>
                </div>
            </div>
            <div class="col-md-6 align-items-center">
                <p> </p>
                <hr style="width:75%; margin: auto;">
                <p> All Rights Reserved. LA Nuñez; LA Workspace 2022. <br> Social Media Icons created by <RouterLink style="text-decoration:none;" to="https://www.flaticon.com/authors/riajulislam/others" target="_blank" title="linkedin icons"> riajulislam - Flaticon</RouterLink></p>
                
            </div>                
        </div>
    </div> 
   
</template> 