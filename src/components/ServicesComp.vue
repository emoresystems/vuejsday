<template>
  <h2>student list</h2>
  <div class="parent">
    <div v-for="(blog, index) in blogs" :key="index" class="card">
      <h3>{{ blog.id }}</h3>
      <h4>{{ blog.title }}</h4>
      <p>{{ blog.body }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "ServicesComp",
  data() {
    return {
      blogs: [
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
        {
          id: 2,
          title: "qui est esse",
          body: "est rerum tempore qui neque nisi nulla",
        },
        {
          id: 3,
          title: "ea molestias quasi exercitationem ",
          body: "nmolestiae porro eius odio et labore et velit aut",
        },
      ],
    };
  },
};
</script>
<style scoped>
.parent {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}
.card {
  background-color: chocolate;
  color: white;
  padding: 5px;
  width: 250px;
  height: 250px;
  margin: 5px;
}
</style>
