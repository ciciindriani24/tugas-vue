<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt="Persib logo" image-url="https://upload.wikimedia.org/wikipedia/en/thumb/1/10/Persib_logo.svg/1200px-Persib_logo.svg.png">
          Persib
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Home</NavbarLink>
          <NavbarLink link="#">Media</NavbarLink>
          <NavbarLink link="#">Store</NavbarLink>
          <NavbarLink link="#">Tiket</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>
