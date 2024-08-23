<script>
    import Appointment from '$lib/components/Appointments.svelte';
    import Clients from '$lib/components/Clients.svelte';
    import ClientDetails from '$lib/components/ClientDetails.svelte';
  </script>
  
  <svelte:head>
    <title>Home</title>
    <meta name="description" content="Veterinarian - part 1" />
  </svelte:head>
  
  <div class="container w-full mx-auto">
    <section class="mt-10">
      <h2 class="text-6xl">Appointments</h2>
    </section>
    <section class="flex flex-col lg:flex-row mt-5">
      <div class="lg:basis-4/6 bg-slate-50 rounded-lg p-10 lg:mr-8">
        <Appointment />
      </div>
      <div class="lg:basis-2/6 bg-slate-50 rounded-lg p-10 sm:mt-4 lg:mt-0">
        <ClientDetails />
      </div>
    </section>
  </div>
  <div class="container w-full mx-auto mt-4">
    <section class="mt-4">
      <h2 class="text-4xl">Clients</h2>
    </section>
    <section class="flex flex-col lg:flex-row mt-5">
      <div class="lg:basis-4/6 bg-slate-50 rounded-lg p-10 lg:mr-8">
        <Clients />
      </div>
    </section>
  </div>
  
  <style>
  </style>