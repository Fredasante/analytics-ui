<template>
  <section class="grid gap-5 md:grid-cols-2">
    <!-- revenue card -->
    <div class="rounded-lg bg-card border p-6">
      <div class="flex items-center justify-between">
        <p class="text-sm font-medium">Total Revenue</p>
        <span class="shrink-0">
          <Icon
            name="heroicons:banknotes"
            class="w-4 h-4 text-muted-foreground"
          />
        </span>
      </div>

      <p class="text-xl mt-1.5 font-extrabold">$143,620.00</p>
      <p class="text-xs text-muted-foreground">
        20% more than last month's revenue
      </p>
    </div>

    <!-- sales card -->
    <div class="rounded-lg bg-card border p-6">
      <div class="flex items-center justify-between">
        <p class="text-sm font-medium">Sales</p>
        <span class="shrink-0">
          <Icon
            name="heroicons:credit-card"
            class="w-4 h-4 text-muted-foreground"
          />
        </span>
      </div>

      <p class="text-xl mt-1.5 font-extrabold">$57,120.00</p>
      <p class="text-xs text-muted-foreground">
        15.5% more than last month's sales
      </p>
    </div>
  </section>
</template>

<script lang="ts" setup></script>

<style></style>
