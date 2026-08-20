Example that Shoria has created, right? If you can come up with this script, it will be helpful. Like, you can create, like, all the external tables at one go. Okay. So, So basically we are identifying the one which doesn't have like a P-Lab or a broad suffix. Yeah, so, so, so for you, um, the task is, any schema that you are seeing here, under high medical store. Right? It doesn't start with, um, E lab, right? Okay. At this in your in your list. Okay? So example could be like these are the all five, all schemas. But if you check the message I pasted in the chat, analytics, right? Um, let me know if you want me to bring this thing here on the screen as well. Excluding this remaining ones. Yes, we need to exclude these schema. Because your focus is only on without broad lab prefix, right? Um, so, you can exclude analytics schema. Your 1st thing that that appears on this admin advantage, PII. Okay. Here we have 2 tables. And the reference part is coming from plot left storage income. Instead, we want cable creation based on the broad, broad data link. Okay. Right? And that's where our script becomes something like, you know, create external table. Tickima, which is large schema, table name, and then location. Here, you are going to make a change, storage account name. So, basic in P-Lab, we are creating, currently we have P-Lab path. We are changing it to Broad path. Changing a schema to prod. Yes, exactly. Okay. And that we require for the uh, the schema. Up until it starts with elap. I have also exploded anything that starts with OPS clean service line. Um, And then ISP Steve, too. So you can map it back to this list. Okay, so it is easier for you to identify which ones are in our scope. Okay. So, if, like, you both can tickle these, uh, so I'll just, like, uh, I'll let Melvin here. And sure, yeah, I'm adding you to this one. Um, Shawya, can you take a look into the view as well? Uh, views for which one? Uh, views for product. So anything that starts with broad lab, similar to, like, table, like, If there are any examples that show you.





This reason, category, and subcategory, is going to, uh, remember, I was explaining you, okay, like, for drug, we have some other, then health and dental has its own, and then life has its own reason and sub reason, right?

So, For example, for drug, it's gonna come from, okay, look at this table, it's gonna come from the CDM drug table, which has the ESC common indicator.

And that ties into the claim line item table, basically.

So, that's where we're going to get the reason and the sub reason.

So the drug reason will come from here.

The health and dental reason will come from this table.

And then the life claims reason and sub reason I've already added in that table itself.

So we have the reason and some reason for life claims out there.

Okay, so, because I was looking into the table's actual tables.

So which one is the actual?

Solid?

I'll tell you, sir.

Okay, so let's go one by one for drug.

It's, I'll give you the P lab tables, and then it'll be the same in fraud.

Oh, this is gonna be...

So this is the table to get the drug reason.

Can you do it, describe on it?

So you will know the problems?

So which colour?

So this is the one?

EST common indication.

So each table has its own category subcategory for this.

Yes, exactly.

So, drug, like, each table, as in, so, if you remember our overall architecture, it's basically, we have two main tables, right?

One is this claim line item table, which I was explaining to you is at the claim line level, like our fact table, and these are our dimension tables, where we have a mapping for drug, which ties back to the fact table, and then we have a mapping for benefit, which also ties back into the fact table.

And then this is our 2nd factable life claims, which already has the reason and sub reason in it.

So if I query that table.

So, you see, this table already has the death reason and the sub reason.

But that is category, right?

Is it, is it same?

Yeah, so, like, yeah, cat, okay.

Maybe that's the country.

Like, category and subcategory is the same as reason and sub reason.

Okay, okay, so maybe that's caused the confusion, because I was looking for...

Oh, like the category field.

Okay, okay.

So this is, yeah.

So, category and subcategory is basically just the reason and the sub reason.

So this is our reason.

Yeah.

Yeah, that makes sense for him, because I was looking for actual category.

I thought reasons.

Oh, okay, okay, got it.

Yeah, so on our side, we call it reason, and they've called it category.

That's it.

Okay, okay.

That should, then we have.

So which table to look for each, what are the two tables?

So like one is drug again.

So, yeah, let me go.

So, one is job, one is CDM benefit, um, which is, like, very fun too.

This one.

And our fact papers are...

This is our fact to do.

And this is our second time.

Okay.

So those are the five tables that we need to work with, basically.

