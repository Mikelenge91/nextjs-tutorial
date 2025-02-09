## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

# nextjs-tutorial

route.ts will look differently then the code provided from teh tutorial. I kept getting an error during the seeding step, so i asked chatGPT for help. what is in there currently is what chat suggested, and the reasons are below:
        Changes & Improvements:
            1. createExtension function: This function ensures that the uuid-ossp extension is created only once at the beginning of the migration process.
            2. Transaction (sql.begin): All seed functions are wrapped inside a transaction. This ensures that if one part of the seeding process fails, none of the changes are committed to the database.
            3. Error handling: I've added error.message to the response to give more details about the error in case of failure.
