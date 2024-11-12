## Tage bis Weihnachten:

Weihnachten: 
<script format="relativetime" unit="day" locale="de">
// Datum von Weihnachten
const christmasDate = new Date('2024-12-24');
// Get the current time
const currentDate = new Date();
// Unterschied in Millisekunden berechnen
const differenceInMs = currentDate - christmasDate;

// Millisekunden in Tage umwandeln
const differenceInDays = differenceInMs / (1000 * 60 * 60 * 24);
// Umrechnen in volle Tage
const WeihnachtsCountdown = Math.floor(differenceInDays);

// Return result
-WeihnachtsCountdown
</script>
!