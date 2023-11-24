<script setup lang="ts">
useSeoMeta({
  title: 'JIANGXUE.ORG 江雪 - Edge Research and Support',
  ogTitle: 'JIANGXUE.ORG - Edge Research and Support',
  description: 'Explore the forefront of edge computing research and support at Jiangxue.org, a self-organized entity with non-profit characteristics driven by a distributed network and sustained through blockchain finance.',
  ogDescription: 'Discover the latest in edge computing research and support at Jiangxue.org. We are a self-organized entity with non-profit characteristics, utilizing a distributed network and blockchain finance to address evolving security threats.',
  ogImage: '/ogImage/ogTitle.png',
  ogUrl: 'https://jiangxue.org/',
  appleItunesApp: 'Jiangxue',
  twitterCard: '/ogImage/twitterCard.png',
})</script>

<template>
  <div class="hello">
    <div class="nav">
      <NuxtLink to="/" activeClass="active-link">/</NuxtLink>
      <NuxtLink to="/about" activeClass="active-link">About<span>Jiangxue.org</span></NuxtLink>
      <NuxtLink to="/project" activeClass="active-link">Project<span>Jiangxue.org</span></NuxtLink>
      <NuxtLink to="/academic" activeClass="active-link">Academic<span>Jiangxue.org</span></NuxtLink>
      <NuxtLink to="/awards" activeClass="active-link">Awards<span>Jiangxue.org</span></NuxtLink>
      <NuxtLink to="/news" activeClass="active-link">News<span>Jiangxue.org</span></NuxtLink>
    </div>
    <NuxtLayout name="logo" />
    <NuxtPage />
  </div>
</template>

<style scoped>
.hello {
  font-size: 1rem;
  padding: 2rem;
}
.nav a {
  margin-left: 15px;
  display: block;
  text-decoration: none;
  font-weight: 500;
  color: #cacaca;
}
.nav a span {
  color: transparent;
}
.active-link {
  color: #1345FF !important;
}
</style>
