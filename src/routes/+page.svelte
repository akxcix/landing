<script>
	import Button from "../lib/Button.svelte";

</script>
<page>
    <h1>
        Wanderfusion
    </h1>
    <h1>
        The Ultimate Group Travel Planner
    </h1>    
    <h3>Plan. Propose. Perfect.</h3>
    <p>Traveling with friends and family just became a whole lot easier. Wanderfusion is your all-in-one solution to plan trips with your loved ones. Say goodbye to long chats and scattered plans. With Wanderfusion, every decision is collective, every plan is synchronized.</p>
    <h2>Features:</h2>
    <ul>
        <li><strong>Slot Selection for Travel:</strong> Propose your travel time slots and let your friends overlay theirs. Find the perfect time window where everyone's available.</li>
        <li><strong>Group Input:</strong> Let everyone voice their preferences. Whether it's destination ideas or dining spots, group decisions are now genuinely democratic.</li>
        <li><strong>End-to-End Planning:</strong> From selecting travel dates to itinerary planning, Wanderfusion offers a comprehensive trip planning experience.</li>
        <li><strong>Notifications & Updates:</strong> Stay in the loop with real-time notifications whenever someone proposes a change or confirms a plan.</li>
        <li><strong>Seamless Integrations:</strong> Sync your calendar, flights, and hotel bookings. Everything you need, all in one place.</li>
    </ul>
    
    <a href="/"><img src="/logo.png" alt="wanderfusion logo"></a>

    <p><strong>Be One of the First to Experience Wanderfusion!</strong><br>
        We're getting ready to launch. If you're as excited as we are and want to be one of the first to try Wanderfusion, sign up for our waitlist.</p>
            
    <spacer></spacer>
    <div class="waitlist">
        <Button href="https://forms.gle/5bWsW4ryMKCAxCGf7" text="Join the waitlist!"></Button>
    </div>
</page>

<style>
    page {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        max-width: 1000px;
        padding: 20px;
    }

    spacer {
        flex-grow: 1;
    }

    img {
        max-width: 400px;
        height: auto;
    }
    

    .waitlist {
        padding: 40px;
    }
</style>
