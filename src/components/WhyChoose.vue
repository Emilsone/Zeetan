<template>
<section>
	<div class="container py-5">
                <div class="row align-items-center">
                    <div class="col-sm-4">
                        <h1 class="mt-4 mt-sm-0"><span>Why </span> <br> Choose Zeet</h1>
                        <p class="my-2 mb-md-4"></p>
                        <!-- <a href="" class="btn btn-wine px-4 py-2">Get in Touch</a> -->
                    </div>
                    <div class="col-sm-8">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum quod cum ea atque, delectus numquam laboriosam cumque officiis voluptate accusantium blanditiis iusto totam fugit repellendus alias molestias ab perspiciatis amet.</p>
                    </div>
                </div>
                <ZeetCard />
            </div>
</section>
</template>
<script>
import ZeetCard from "@/components/ZeetCard.vue";
export default {
  name: "WhyChoose",
  components: {
    ZeetCard
  }
};
</script>

