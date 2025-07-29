<script setup lang="ts">
import { Tabs, TabsContent, TabsList, TabsTrigger } from './Tabs'
</script>

<template>
  <Tabs default-value="account" class="w-[400px]">
    <TabsList>
      <TabsTrigger  value="account">
        Account
      </TabsTrigger>
      <TabsTrigger value="password">
        Password
      </TabsTrigger>
    </TabsList>
    <TabsContent value="account">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, quaerat? Perferendis, quibusdam molestias eum quam nulla, similique iusto, esse accusamus distinctio dignissimos ut. Cumque iusto aut illum debitis, obcaecati nostrum.
    </TabsContent>
    <TabsContent value="password">
      Change your password here.
    </TabsContent>
  </Tabs>
</template>