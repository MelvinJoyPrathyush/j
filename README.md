Uh, you are supposed to maintain a phone code changes, great, uh, uh, like set up all necessary code and everything.

Okay.

Uh, I'm not sure on that part, whether, sorry, Sauriya did it, but he asks us to set up the call with you regarding this.

They, the crowd, the cloud catalogue module is already approved, right?

Are you aware of that?

A CloudCatlug models are probably a good CloudCatlug.

But copying the CloudCatlug, they are set up our, they are supposed to set up our own repository with our own kind of phone code.

So, we will be, like, using, following the examples of what's then in the cloud catalogue, but we will be setting up our role in our concord.

So that was what we were supposed to do.

Sure, you did that.

Here, let me share my screen.

Sure.

Wait, do you mean?

Sure, you said he set up this briefing.

Like, I created this supposedly, I remember creating it, but the problem is I'm in this repository, like, right now.

And what I see is it's pretty minimalistic.

There is nothing comparatively what we are using, but we are seeing in cloud catalogue.

So, for example, to create the capacities, uh, we need few futures, which is already there, and, like, yard kettla, but, but I don't see anything here.

Okay.

So, so what are the next steps on this?

Like, uh, like, in terms of setting up this, uh, fabric capacity.

I have to, uh, start working on the, uh, Telephone code.

So, okay, for example, if you see, I share, can you go into the Ingram is folder, please?

Anyone, any, any part.

So this is, there is nothing here.

It's just states the subscription we are going to use, and what is the environment we are using, and what location, like what region it is there.

We are, we are supposed to set up the great tabric capacity, prove this turf of goods that we have to give a name, we are at all of those.

We need to set up a, we should have a setup file separately, where we are creating all the modules, and calling those modules in the stuff of good, and passing money in the values from here.

Oh, that's what we, yes, we have to do first.

So that should be done for all the environments, right?

I would prefer it that way.

I don't know why, um, He started like this, but um.

There is a main dot TF file, right out, right in the telecom folder.

Which is if you see here it's talking about the resource group, fabric capacity and all.

So, we are setting up a variable, to get a fabric capacity name from the actuality of worse file. Correct?

Line number 35.

Okay.

We have this, we have assigned a variable to get a fabric capacity name from our actual telephone code.

So that's what we have to make changes.

So if you go to a TFOS file, that's why we are supposed to pass the capacity name on all of those.

Can you go back one level?

So which one?

In inside environments.

We have 3 files for environments, right?

So we are supposed to pass the capacity game and everything from this one.

Okay.

Yeah, that's the changes we have to do.

We have to take care of.

Like, is this just a placeholder right now?

So, oh, this is the just setup file, like, um, auto fables.

So, we, setup file is where, where we create the modules, that is supposed to be used in our actual terrap on code.

So we cannot, we, this is to reuse in all the environments.

So we are just setting it up, setting up a module for it.

And this model will be called in our, the environment specific tier was filed.

So for example, uh, I think you have, uh, Sheher, you have access to all the adversities, right?

Yeah.

Injection setup, please.

Can you go to telecom?

Okay, so if you see setup area.TM, this is where we are supposed to create all the modules, so we have created all the modules, saying that if you see line number 15, model data factory, which means whatever it's being passed, value being passed to this model, may be reflected in the ADF, we are creating a rush report.

Okay.

So, and main dot TF should be empty.

There should be nothing in it, main dot TS.

It should only have the global settings, nothing else.

Okay.

So, we have to do the setup for TF as well as, if you see uh, variables non-prof- DF, yeah, can you open that, please?

So they're calling that module here.

If you stole a little bit down, or...

Four more, please.

Yeah, wait here.

So, line number 109.

So that's what they're calling the module.

So, we are parking the data factory name.

And the private endpoint and everything that has been associated to the rate of factory from here.

But the, this value, how it's being used, it's been set up in the setup. Area file.

Okay.

Yeah.

We have to do the similar pattern.

And then, so, similar to how here, like, the main TF is kind of empty.

We wanted you for that there, and then use, like, the variable files, as, the variable files and the setup file.

For the valuable files of what you have, set it up as, uh, inside the end of one folder, in the fabric set up repository.

Yeah.

Okay.

But we may have to add the name, cap capacity name, and all of those details in that pile.

Okay.

Also, we have to set up the roller cement and all of those as well.

And we can use the ingestion setup as kind of like a reference on, you know, what we should be aiming for.

We can, is.

Okay.

I don't think I have any more questions, like, I'll probably just look through the ingestion setup.

And then maybe we can be later if, like, more questions come up.

But in the meantime, Melvin can work together.

Um, Malvin, did you have any other questions?

Yeah, I think I don't have much more questions on it.

I think I just got an idea on this.

You know, we can work together to understand it more.

Because I haven't done this before, so I just want to know, like what are the steps involved?

I haven't gone through the cloud capacity yet.

I will go through that, and I will also suggest what needs to be done probably before the end of this week.

Is there anything else?

Is there any, like, document for this?

Like, anywhere where that we can defer confluence?

I don't think so.

Okay.

So, so here, you have any questions, uh, we can wrap up.

Yeah, we're good to wrap up.

Mmmm.

Okay.

Okay.

Thanks, everyone.

Thank you.

Thank you.

Bye.

Bye. 

Like is this just a placeholder right now? So this is the set up file like all those papers. So we... set up file is where we create the modules that is supposed to be used in our actual data form code. So this is to reuse in all three environments. So we are just setting it up, setting up a module for it. And this module will be called in our general specificity of our file. So for example, I thought you have, she had access to all the data positives, right? Yeah, and you do an injection set of please.
very good enough. Okay, so if you see setup area.tm
This is where we are supposed to create all the modules. So we have created all the modules in that, if you see line number 15, module data factory, which means whatever it's being passed, value being passed through this module, will be reflected in the idea we are creating an Azure portal. So and main.tf should be empty. There should be nothing in a main.tf. actually only have the global settings nothing else. Okay. So we'll have to do this setup for TF as well as if you see variables non-prod.fdf.f.s, that can open that list. So they are calling that module here. If you scroll a little bit down.
Two more please. So line number 109. So that's where they are calling the module. So we are passing the data factor name and the private endpoint and everything that is also related to the data factor from here. But these values, how it's being used, it's been set up in the setup.area file.
Okay. Yeah. Well, we have to do the similar pattern.
And then so similar to how here like the mean to have this kind of empty, we want it in for that there and then use like the variable files as the variable files and the set up file. So the variables I filed the word here of said it was insurgent, an environment forward in the fabric set up repository. But we may have to add the name, cap capacity name and all of those details in that file. Okay.
also, you know, basically, the oldest and most of those as well. And we can use the ingestion set up as kind of like a reference on, you know, what we should be aiming for. You can, yes. Okay.
I don't think I have any more questions. I probably just looked through the ingestion setup and then maybe we can meet later if I have more questions than the meantime you now then can work together. And Maul, can you have any other questions? Yeah, I think I don't have much more questions on it. I think I just got an idea on this. We can work together to understand it more. Because I haven't done this before, so I just want to know what other steps you need.
I haven't gone through the cloud catalog version of fabric capacity yet. I'll go through that and I will also suggest what needs to be done probably before the end of the week. Yeah.
Is there anything else? Is there any document for this, like anywhere that we can different confluence? I don't think so. But there are no documents that does come in now.
So, so how do you have any questions? So, we can wrap up. Yeah, we're good to wrap up. Okay. Thanks everyone. Thank you. Thank you. Bye.




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

