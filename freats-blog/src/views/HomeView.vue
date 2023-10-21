<script setup>
import TheNavigation from '../components/TheNavigation.vue'
import TheHighlightBanner from '../components/TheHighlightBanner.vue'
</script>

<template> <!--turn into a card-->
  <div class="home-container">
    <TheNavigation />
    <TheHighlightBanner/>
    <h1 class="latest">What's New...</h1>
    <div class="main-container columns">
      <div class="column">
        <div class="new-post-homepage card" @click="click">
          <div class="new-img-homepage card-image">
            <img src="../../public/pilot.jpg" class="preview-image" />
          </div>
          <div class="card-content">
            <h1 class="preview-title">Pilot</h1>
            <div class="minuteread metadata-text">8 Minute Read</div>
            <div class="namedate">
              <div class="metadata metadata-text">Fred He</div>
              <div class="metadata metadata-text">2023/10/19</div>
            </div>
            <h1 class="preview-content">
              Do you know how all the Netflix shows you watch usually have their first episode titled
              “Pilot”? I thought it was pretty cool until I realized it acted as an episode to evaluate
              the show’s potential for success. Now, I wonder about all the pilot episodes I’ve never
              seen. Anyway, I titled this post “Pilot” to mark the beginning of FREATS and have
              something cool to look back on. <span class="read-more-text" @click="click">Read More</span>
            </h1>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="new-post-homepage card" @click="click">
          <div class="new-img-homepage card-image">
            <img src="../../public/pilot.jpg" class="preview-image" />
          </div>
          <div class="card-content">
            <h1 class="preview-title">Pilot</h1>
            <div class="minuteread metadata-text">8 Minute Read</div>
            <div class="namedate">
              <div class="metadata metadata-text">Fred He</div>
              <div class="metadata metadata-text">2023/10/19</div>
            </div>
            <h1 class="preview-content">
              Do you know how all the Netflix shows you watch usually have their first episode titled
              “Pilot”? I thought it was pretty cool until I realized it acted as an episode to evaluate
              the show’s potential for success. Now, I wonder about all the pilot episodes I’ve never
              seen. Anyway, I titled this post “Pilot” to mark the beginning of FREATS and have
              something cool to look back on. <span class="read-more-text" @click="click">Read More</span>
            </h1>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="new-post-homepage card" @click="click">
          <div class="new-img-homepage card-image">
            <img src="../../public/pilot.jpg" class="preview-image" />
          </div>
          <div class="card-content">
            <h1 class="preview-title">Pilot</h1>
            <div class="minuteread metadata-text">8 Minute Read</div>
            <div class="namedate">
              <div class="metadata metadata-text">Fred He</div>
              <div class="metadata metadata-text">2023/10/19</div>
            </div>
            <h1 class="preview-content">
              Do you know how all the Netflix shows you watch usually have their first episode titled
              “Pilot”? I thought it was pretty cool until I realized it acted as an episode to evaluate
              the show’s potential for success. Now, I wonder about all the pilot episodes I’ve never
              seen. Anyway, I titled this post “Pilot” to mark the beginning of FREATS and have
              something cool to look back on. <span class="read-more-text" @click="click">Read More</span>
            </h1>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="new-post-homepage card" @click="click">
          <div class="new-img-homepage card-image">
            <img src="../../public/pilot.jpg" class="preview-image" />
          </div>
          <div class="card-content">
            <h1 class="preview-title">Pilot</h1>
            <div class="minuteread metadata-text">8 Minute Read</div>
            <div class="namedate">
              <div class="metadata metadata-text">Fred He</div>
              <div class="metadata metadata-text">2023/10/19</div>
            </div>
            <h1 class="preview-content">
              Do you know how all the Netflix shows you watch usually have their first episode titled
              “Pilot”? I thought it was pretty cool until I realized it acted as an episode to evaluate
              the show’s potential for success. Now, I wonder about all the pilot episodes I’ve never
              seen. Anyway, I titled this post “Pilot” to mark the beginning of FREATS and have
              something cool to look back on. <span class="read-more-text" @click="click">Read More</span>
            </h1>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    click() {
      console.log('hello')
      this.$router.push('/posts/6531d94d0fa3f3d231200d37')
    }
  }
}
</script>
