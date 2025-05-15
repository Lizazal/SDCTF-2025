# Search for Piotr

Team: st0p_cyb3rbu11ying

## Contents

[Task description](#task-description)

[Initial information gathering](#initial-information-gathering)

[Day 4. May 7th flag](#day-4-may-7th-flag)

[Day 5. May 8th flag](#day-5-may-8th-flag)

[Day 6. May 9th flag](#day-6-may-9th-flag)

[Day 3. May 6th flag](#day-3-may-6th-flag)

[Day 2. May 5th flag](#day-2-may-5th-flag)

[Day 1. May 4th flag. The last one.](#day-1-may-4th-flag-the-last-one)

[Conclusion](#conclusion)

## Task description

This OSINT consists of 6 similar parts: finding Piotr's whereabouts. The exact task descriptions look like:

- OSINT/Piotr's Day Off: Day 1

  Multiple Authors
  
  18 solves / 100 points
  
	ACM at UCSD has contracted us to find the whereabouts of its board member Piotr, last seen at the Sun God Festival in SD. He is currently at large… can you track him?
After leaving San Diego, which city was Piotr in on Sunday, May 4th?

	Flag format is only the city name with proper capitalization as it appears on en.wikipedia.org (e.g. San Diego)
	 
- OSINT/Piotr's Day Off: Day 2

	Multiple Authors

	31 solves / 100 points

  Which city did Piotr visit on Monday, May 5th?

  Flag format is only the city name with proper capitalization as it appears on en.wikipedia.org (e.g. San Diego)
  
- OSINT/Piotr's Day Off: Day 3

	Multiple Authors

	12 solves / 100 points

	Which city did Piotr visit on Tuesday, May 6th?

	Flag format is only the city name with proper capitalization as it appears on en.wikipedia.org (e.g. San Diego)
- OSINT/Piotr's Day Off: Day 4

	Multiple Authors

	30 solves / 100 points

	Which city did Piotr visit on Wednesday, May 7th?

	Flag format is only the city name with proper capitalization as it appears on en.wikipedia.org (e.g. San Diego)

- OSINT/Piotr's Day Off: Day 5

	Multiple Authors

	24 solves / 100 points

	Which city did Piotr visit on Thursday, May 8th?

	Flag format is the only city name with proper capitalization as it appears on en.wikipedia.org (e.g. San Diego)

- OSINT/Piotr's Day Off: Day 6

	Multiple Authors

	21 solves / 100 points

	Which city did Piotr visit on Friday, May 9th?

	Flag format is only the city name with proper capitalization as it appears on en.wikipedia.org (e.g. San Diego)

## Initial information gathering

The most meaningful part of the task description is: ACM at UCSD has contracted us to find the whereabouts of its board member Piotr, last seen at the Sun God Festival in SD. He is currently at large… can you track him?

What do we have from the beginning? Some person – **Piotr** – is a board member of **ACM at UCSD**. Piotr left San Diego and travelling somewhere **between 4th and 9th May**. The task is – find out in which cities Piotr spent time on May 4th, 5th, 6th, 7th, 8th and 9th. Let’s go.

First of all – who is Piotr? Let’s google the whole thing we know *Piotr ACM at UCSD*.

<p align="center">
  <img src="https://github.com/user-attachments/assets/4262aca1-27fa-44b5-98d8-7e59ce7b7533" alt="Googling 'Piotr ACM at UCSD' screenshot"/>
</p>

We immediately get two links: **LinkedIN** and **ACM at UCSD site**. Firstly, it’s important to *make sure* that LinkedIN account belongs to our Piotr, not some *other*, so for now we’ll skip it. Let’s start from ACM at UCSD site and look for Piotr here.

Immediately upon opening the site, we see a useful page entitled:

<p align="center">
  <img src="https://github.com/user-attachments/assets/c55b9de2-0627-4d56-9b87-964943e665d0" alt="Meet the Board"/>
</p>

So we can immediately start searching for Piotr on this exact page, because Piotr is a board member. Let’s Look for Piotr using **Ctrl+F**:

<p align="center">
  <img src="https://github.com/user-attachments/assets/6189e74f-6afa-40e8-ae40-4c99b8052b1a" alt="Piotr is found"/>
</p>

There’s only one match. What info do we get here? Position (AI Software Dev), some avatar, full name (Piotr Sultanbekov, will be useful 10000%), LinkedIN and email.

Let's write out the new info:

* **Name**: Piotr Sultanbekov
* **Email**: piotr@acmucsd.org
* **LinkedIN**: https://www.linkedin.com/in/piotr-sultanbekov/ (yes, this is the link we got earlier by googling, but now we are sure that this is the same person we’re looking for. It’s always important to be sure)

Okay, let’s go to LinkedIN.

<p align="center">
  <img src="https://github.com/user-attachments/assets/6bb7bbfc-6798-419f-bc8b-daf4e2a707ca" alt="GitHub link & contact info"/>
</p>

There’s a link to **GitHub**. There was also some info about Locations (on-site), which included
> San Francisco Bay Area · New York, United States · **Baikonyr, Kyzylorda Region, Kazakhstan**

But it's been removed for now, so you can just take my word for it. However, there's more information:

<p align="center">
  <img src="https://github.com/user-attachments/assets/e9f95149-c089-4a5d-b63c-835cbd581f80" alt="Education: UC San Diego"/>
</p>

Peter studies at the **UСSD** and is a member of a certain **Smash Club**.

If we look at Piotr's subscriptions, we will see that Piotr is subscribed to Ditto AI.

<p align="center">
  <img src="https://github.com/user-attachments/assets/bb9eb335-1fab-46df-97f0-287f21bb618a" alt="Ditto AI"/>
</p>

Peter even left a comment about wanting to do an internship with them.

<p align="center">
  <img src="https://github.com/user-attachments/assets/692e76f9-fd5b-4138-bbd7-b821473e4efa" alt="Ditto AI hiring"/>
</p>

This **Ditto AI** may be somehow useful in future.

At the beginning Piotr’s LinkedIN research, we found a link to **GitHub**. Let’s finally use it: https://sultangamer06.github.io/ What useful information is possible to find here?

<p align="center">
  <img src="https://github.com/user-attachments/assets/5cbb6b83-34c4-4543-8a66-6f95caef10b4" alt="Same email and name"/>
	<br>
	<img src="https://github.com/user-attachments/assets/efd07e73-ac7a-4dac-bfff-ae9546a5dc87" alt="Same avatar"/>
</p>

Here're same avatar and name with email that we've found already. This proves that this is most likely the site of our Piotr. New nickname: **sultangamer06**. What else can be found here?

<p align="center">
  <img src="https://github.com/user-attachments/assets/10abe174-956f-41b5-a6c9-66e5b5d311a6" alt="Piotr's preferations"/>
</p>

Piotr is intersted in an internship for Summer 2025 at FAANG, a bored member at ACM AI. **And loves super smash bros, main Isabelle here**. Some of this information may be useful to us in the future, so let's write it down.

From the git-made site let's move on to the GitHub and examine it: https://github.com/sultangamer06

<p align="center">
  <img src="https://github.com/user-attachments/assets/545ef680-b7b4-4427-a800-e1f8e4797168" alt="Piotr's GutHub"/>
</p>

One repo with main activity in April. What's inside?

<p align="center">
  <img src="https://github.com/user-attachments/assets/1866795c-dd42-485c-809a-5657ea173628" alt="Piotr's GutHub repo"/>
</p>

Looks like a typical repository. In terms of OSINT there are two things we can focus on: commits or activity.

<p align="center">
  <img src="https://github.com/user-attachments/assets/0015160b-7a97-456d-a328-354dc8f9582c" alt="Piotr's GutHub repo: commits and activity"/>
</p>

We can start from commits to get some surface information, and then go deeper with activity.

The commits mostly show the normal process of creating a site. Let's try ‘patch’ to check the email here too:

<p align="center">
  <img src="https://github.com/user-attachments/assets/6bc112d3-29ab-463f-94ef-56fbb3245628" alt="Piotr's GutHub repo: patch"/>
</p>

Just the same email we've seen before. Let's look further.

<p align="center">
  <img src="https://github.com/user-attachments/assets/6e77ca32-2774-4765-a906-24b4a2d14ea2" alt="Piotr's GutHub repo: email and username commits"/>
</p>

Changing email and GitHub username, but nothing that we haven't seen before.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a358ac38-6c11-4a22-9fa5-bf35097ec818" alt="Piotr's GutHub repo: Xeets"/>
</p>

This's more interesting. Some strange sentence that was removed about **Xeets on X**. So where's Piotr's Xeeter?

It's time to check the activity.

<p align="center">
  <img src="https://github.com/user-attachments/assets/51080cb1-c7ba-419f-b1a0-8dc180de3f38" alt="Piotr's GutHub repo activity: OOPS"/>
</p>

Looks a little bit suspicious, right? Let’s compare changes for this one.

<p align="center">
  <img src="https://github.com/user-attachments/assets/4d7287b9-f6ca-4a31-aae4-eea3b6408f34" alt="Piotr's GutHub repo activity: Compare changes"/>
</p>

One more bit of info. Congrats! Now we have a Xeeter: **su1tangam3r**

Just to be sure, let’s check both sultangamer06 and su1tangam3r by Sherlock (there’re other tools actually, like whatsmyname (online), maigret, etc., depends only on personal preferences)

Actually we can use one common query, just put a space between the names.

<p align="center">
  <img src="https://github.com/user-attachments/assets/1d16ab06-cfad-4070-8209-e750f212efee" alt="Sherlock"/>
</p>

These are usually just noise and nonsense.

<p align="center">
  <img src="https://github.com/user-attachments/assets/1f376c24-3fcf-4f98-8e5b-8bdfff0f1d01" alt="Imgur"/>
</p>

Github is where we started. **Imgur**, YouTube and second-twitter are may worth checking out in future.

**Imgur**: https://imgur.com/user/sultangamer06.

Twitter2 https://x.com/sultangamer06 - doesn't exist.

YouTube https://www.youtube.com/@sultangamer06 - has nothing.

<p align="center">
  <img src="https://github.com/user-attachments/assets/465a9dfd-0f4c-47e7-aefa-10bf0020e4af" alt="Nothing"/>
</p>

For the second username we get only X that we know and some typical noise.

Let's continue search using sultangam3r X account: https://x.com/su1tangam3r

<p align="center">
  <img src="https://github.com/user-attachments/assets/f0d17282-f1e2-42cd-827b-e50c26c8f500" alt="NewProfilePic"/>
</p>

Similar photo, again UCSD (where Piotr studies), and also activity at the end of April. Of course, we got this X acc from a quite reliable source, but it never hurts to make sure once again that this is the same Piotr.

<p align="center">
  <img src="https://github.com/user-attachments/assets/bbdacb23-5a4e-468a-8f82-f3dac817c52d" alt="Posts about Isabelle and leaving San Diego"/>
</p>

Posts about Isabelle (we remember, that Piotr mains Isabelle) and leaving San Diego - things still match up.

<p align="center">
  <img src="https://github.com/user-attachments/assets/fdf22e69-2651-4960-acc4-04c4265b6ccf" alt="More Isabelle!"/>
</p>

A little more of Isabel in the background of the profile and in the bio.

<p align="center">
  <img src="https://github.com/user-attachments/assets/83c13c31-53ed-44a3-8f63-5b1abb2987e4" alt="Looking for a girfriend repost"/>
</p>

Reposted something about looking for a girlfriend - matches the subscriptions to Ditto AI.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a6247aa0-4033-4cf8-b06a-322586ab9a69" alt="Truth social?"/>
</p>

Goes somewhere for the truth. Good thing there is a link in the bio:

<p align="center">
  <img src="https://github.com/user-attachments/assets/63937b85-8249-48a2-99bf-e92110e69540" alt="Truth social link."/>
</p>

New link for **truthsocial**: https://truthsocial.com/@sultangamer

Username is just ‘sultangamer’. Probably quite popular, so it would be hard to search, no point in doing that now.

<p align="center">
  <img src="https://github.com/user-attachments/assets/7d169188-a14f-4d5e-9267-435eac0948e2" alt="Thuthsocial: Piotr"/>
	<br>
	<img src="https://github.com/user-attachments/assets/897343d2-c3ba-44a3-9f56-c450df387c36" alt="Thuthsocial: i am Piotr and this is my truth"/>
</p>

Post with the name Piotr, phrase in bio, account created in April - probably our Piotr. The phrase from bio sounds strange, may it mean something? Let's remember it for now.

<p align="center">
  <img src="https://github.com/user-attachments/assets/07bdd4a2-9fbc-4d32-aadd-7eb9ec266fe8" alt="Photo for Geoint"/>
</p>

Post with a picture. Posted on May 7th. Let's assume that this photo was taken and posted by Piotr on the day of visit to this city. Geoint time.

## Day 4. May 7th flag

There's a picture:

<p align="center">
  <img src="https://github.com/user-attachments/assets/f17d8b2b-148a-4748-8a2f-6331e3a5bac0" alt="Photo of Shell with STB bank in the background"/>
</p>

What do we see at the photo? Shell gas station and the STB bank. Shell's are pretty everywhere, so let's google STB Bank.

<p align="center">
  <img src="https://github.com/user-attachments/assets/c44f76ae-d52f-4fdf-a0a6-cdaaa2761bbc" alt="STB bank google info"/>
</p>

We see that this bank is most likely located in Tunisia. We check the bank's logo - it matches what we can see in Piotr's photo.

Reverse image for Tunisia. Refocusing to different places of the image may be needed due to different google lens search results.

<p align="center">
  <img src="https://github.com/user-attachments/assets/f8b05650-5ff4-4721-9c27-7637a7880792" alt="La Goulette"/>
</p>

Some info about La Goulette. It won't cost us anything to try to search and look for Shell gas stations in this place.

<p align="center">
  <img src="https://github.com/user-attachments/assets/7b9a7cdc-d9b2-455c-8685-97488740975a" alt="Shell La Goulette"/>
</p>

There're three of them. Checking one by one find the one from the photo:

<p align="center">
  <img src="https://github.com/user-attachments/assets/d39016bf-5d82-4b7e-bfaf-c2569918858b" alt="Shell La Goulette"/>
</p>

La Goulette is a part of Tunis. Recheck spelling using Wikipedia:

<p align="center">
  <img src="https://github.com/user-attachments/assets/047ec894-a700-475a-a89a-307db678e1b1" alt="Tunis Wikipedia"/>
</p>

The flag for May 7th or Day 4: **Tunis**

## Day 5. May 8th flag

Continue to look at posts in Truthsocial. The very last post there is about Piotr moving to some social where the sky is bluer. The bluest sky social is **Bluesky**. Let's look for Piotr's account in Bluesky.

<p align="center">
  <img src="https://github.com/user-attachments/assets/dd58539d-8221-4700-9ed3-62136086851f" alt="Social where sky is bluer post"/>
</p>

Here it is: https://bsky.app/profile/did:plc:yh7txkrgj7osffw5xffvpjkb Can be found using 'sultangamer' username.

<p align="center">
  <img src="https://github.com/user-attachments/assets/129c0f60-a799-4b28-9100-c948575f9b34" alt="Piotr's bluesky bio"/>
</p>

Humanized Isabella as the avatar and the same library we previously saw as a background image on LinkedIn.

<p align="center">
  <img src="https://github.com/user-attachments/assets/cc9f513f-3151-4093-a798-ffa609c9f649" alt="Piotr's bluesky posts"/>
</p>

A series of posts. Written on May 8th. They're about smash torney - obviously Smash Bros, as we already know, Piotr's a fan, and they play "magic die zusammenkunft" there. Let's translate:

<p align="center">
  <img src="https://github.com/user-attachments/assets/f0e48281-a39f-4c4d-ad14-9aa1a10040af" alt="Translation"/>
</p>

Google says it's 'magic the gathering' from German. Let's google some Smash Bros tournament on May 8th.

<p align="center">
  <img src="https://github.com/user-attachments/assets/e0a5d87d-64aa-44b9-929d-ad08d7c80707" alt="Googling"/>
</p>

This Reddit link seems useful. Let's check it out: https://www.reddit.com/r/smashbros/wiki/events/

<p align="center">
  <img src="https://github.com/user-attachments/assets/99ced95a-8b75-4f43-ae11-554d38f0e196" alt="Tournaments from Reddit"/>
</p>

May 8-11 there was 'Melee im Kornspeicher 2' event. Let's find out more information about it: https://www.start.gg/tournament/melee-im-kornspeicher-2/details May 8th was Thursday.

<p align="center">
  <img src="https://github.com/user-attachments/assets/497061b1-d719-4731-937d-6279bcee640b" alt="Magic the gathering on Thursday"/>
</p>

They played 'magic the gathering on Thursday. Let's check the city spelling using wikipedia.

<p align="center">
  <img src="https://github.com/user-attachments/assets/da25c5e8-9064-45be-a69c-386dfdd091ed" alt="Großlohra wikipedia"/>
</p>

The flag for May 8th or Day 5: **Großlohra**

## Day 6. May 9th flag

Continue to look at posts in Bluesky.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a6f29bc8-1b91-410f-b6da-215d26311988" alt="Bluesky strange post"/>
</p>

On May 9th Piotr wrote "менi iздеме". Let's translate.

<p align="center">
  <img src="https://github.com/user-attachments/assets/351d46be-9029-4f6e-af3e-6698c5e4b737" alt="Translate"/>
</p>

Google says it's Kazakh language. We can link it to LinkedIN information about Baikonur, or just let it go for a moment. However, there're not a lot leads left. We can check imgur:

<p align="center">
  <img src="https://github.com/user-attachments/assets/a2372e0d-7db7-4e70-8e8b-e43c9121bcbc" alt="Almost empty Imgur"/>
</p>

But there is no information there. The only thing left is to try to search further. Firstly, let’s use the full name and try other search engines. Bing and DuckDuckGo - both give us a link to the VK account. Let's see if it suits us: https://vk.com/sultangamer007

<p align="center">
  <img src="https://github.com/user-attachments/assets/b9e66bed-efb6-4994-9db7-179a795b125e" alt="VK page bio"/>
</p>

More Isabelle and UCSD in bio. Probably, that's out Piotr. Let's translate the phrase from bio.

<p align="center">
  <img src="https://github.com/user-attachments/assets/cc8754b6-ad51-45ad-a54c-e8daa9197915" alt="Translating"/>
</p>

The same phrase we saw before in Thuthsocial account.

<p align="center">
  <img src="https://github.com/user-attachments/assets/2cda6fe5-525d-4ede-a47c-dde31b0be06b" alt="Ditto AI mentioned"/>
</p>

Another mention of Ditto AI. Just one more sign that this Piotr is the one we look for.

<p align="center">
  <img src="https://github.com/user-attachments/assets/7ea6c131-0989-42b0-acf1-203d7994db17" alt="Isabelle in space"/>
</p>

This post was published on May 9th. Let's translate the phrase.

<p align="center">
  <img src="https://github.com/user-attachments/assets/2f940b51-29b7-4699-a915-8facbbe027c5" alt="Translating..."/>
</p>

'I'm flying now. Goodbye.' This post also has a geotag - Baikonur. Roscosmos in subscriptions. Everything matches - we return to Baikonur from LinkedIN. Let's check the spelling in Wikipedia:

<p align="center">
  <img src="https://github.com/user-attachments/assets/cb262c5c-0b0f-45f1-a4a3-2a9733fc1b52" alt="Baikonur wikipedia"/>
</p>

The flag for May 9th or Day 6: **Baikonur**. It was spelled differently in LinkedIN, so wikipedia check may be useful.

## Day 3. May 6th flag

Now we have some weird empty **Imgur** and nothing else. This was the tricky part. If we try to google sultangamer06 (we know this nickname from the beginning), we will get some posts:

<p align="center">
  <img src="https://github.com/user-attachments/assets/afe30ec2-ba40-445d-a673-d014f5a85d9a" alt="Googling"/>
</p>

We can open them and look: https://imgur.com/gallery/original-meme-ZlyxHu8

<p align="center">
  <img src="https://github.com/user-attachments/assets/3cc8d5d9-94e0-4739-8d14-ea4f90691c0d" alt="My original meme"/>
</p>

This is just a funny meme. It might be **useful** somehow, but it's not clear yet. Another post we googled: https://imgur.com/gallery/me-epic-YF6TFK7

<p align="center">
  <img src="https://github.com/user-attachments/assets/b0b2a7a5-5b43-4139-a70b-b18cfb0e8b50" alt="Me, epic - img from avatar before"/>
</p>

At least now we know that this is indeed the same Piotr.

But if we try to google ‘sultangamer06 imgur’ or ‘sultangamer06 Tuesday’ (it’s one of the rest weekdays) or even use Google tools and search ‘site:https://imgur.com sultangamer06’, we will get one more *hidden* post:

<p align="center">
  <img src="https://github.com/user-attachments/assets/c485c8fe-19ce-4898-b125-30b437494b0d" alt="Googling for one more post"/>
</p>

There's it: https://imgur.com/gallery/vibess-j6vpDZC

<p align="center">
  <img src="https://github.com/user-attachments/assets/085ddd00-7524-4796-a39d-afda99a838c7" alt="Vibess post with photo from the concers"/>
</p>

> Piotr … listens to magdalena bay … went to her concert on Tuesday

Let’s google this concert: https://buffaloriverworks.com/event/magdalena-bay-imaginal-mystery-tour/

<p align="center">
  <img src="https://github.com/user-attachments/assets/98d0296e-bdd7-447e-b924-50796776bd64" alt="Magdalena Bay tour page for May 6th in Buffalo"/>
</p>

Magdalena Bay tour page - Tuesday May 6th in Buffalo. Let's check Buffalo spelling using wikipedia:

<p align="center">
  <img src="https://github.com/user-attachments/assets/f7e7c3c9-fa26-4abd-92bd-136320f738e1" alt="Wikipedia page for Buffalo"/>
</p>

The flag for May 6th or Day 3: **Buffalo**.

## Day 2. May 5th flag

Where can we look for the rest of the flags? Another tricky part. The first thing we do is try to find Piotr in other popular social networks (Facebook, mastodon, Instagram, theads, etc.), but the name is not enough. We know that Piotr is from UCSD and is a board member of ACM at UCSD, and Piotr is also subscribed to Ditto AI and Plumera everywhere. So we can try looking for Piotr in subscribers.

Finally, we find Piotr’s **Instagram**. I did it via ACM at UCSD subscribers:

<p align="center">
  <img src="https://github.com/user-attachments/assets/ea8782a6-8aa4-45c3-b320-d5d4f1329fa2" alt="Piotr's Instagram"/>
</p>

Piotr's username in Instagram is **sult4n_g4mer**. Piotr’s Instagram can also be found through subscriptions to other users mentioned:

<p align="center">
  <img src="https://github.com/user-attachments/assets/f48bd34d-af73-4d03-8179-810fba24aa48" alt="Plumera subscribers"/>
	<img src="https://github.com/user-attachments/assets/9687cf4e-9206-4436-ac5b-16da13509bac" alt="Ditto AI subscribers"/>
</p>

What can we find on the Instagram page proving that this is the Piotr we're looking for? https://www.instagram.com/sult4n_g4mer

<p align="center">
  <img src="https://github.com/user-attachments/assets/f5a1dfc3-fd99-4999-9f4f-1569e461bf1d" alt="Same university: UCSD"/>
	<img src="https://github.com/user-attachments/assets/73d84330-4ad3-4918-9177-1fb4cea64958" alt="Same library form LinkedIN bio"/>
</p>

Same university as Piotr's, more Isabelle and the library from Piotr's LinkedIN bio background.

Let's look at other posts. There's one posted May 6th with some photo.

<p align="center">
  <img src="https://github.com/user-attachments/assets/955db8ac-31d3-441a-925a-846d72b267be" alt="Piotr's post from Instagram"/>
</p>

Time for geoint! It's important to focus google lens on the part where there is no face, since Google policy prohibits searching for faces, and when google lens sees a face - it stops giving any results.

<p align="center">
  <img src="https://github.com/user-attachments/assets/f0095d46-e74b-4376-8f8d-b91cece87974" alt="Google Lens result is Kitty Hawk"/>
</p>

All results point to Kitty Hawk Pier. Let's check the spelling via wikipedia:

<p align="center">
  <img src="https://github.com/user-attachments/assets/89add75f-dfa7-484a-88f6-d4c99ddb3736" alt="Wikipedia page for Kitty Hawk"/>
</p>

The flag for May 5th or Day 2: **Kitty Hawk**.

## Day 1. May 4th flag. The last one.

Continue to look at posts in Instagram.

<p align="center">
  <img src="https://github.com/user-attachments/assets/81f84e75-0339-4b80-9eea-68c9d166b933" alt="Post about Sun God Festival"/>
</p>

A post about the Sun God Festival (after which Piotr disappeared) with a strange hashtag: **#DontBooliMyWooli**.

There’re two ways to find the last flag. We need another account, but where is it? The strangest thing is this hashtag, it seems quite unique also, so we can try googling it:

<p align="center">
  <img src="https://github.com/user-attachments/assets/72e75561-9c9c-41fc-995c-4e78d97f0ee4" alt="Googling #DontBooliMyWooli"/>
</p>

Here are the results. We already found Insta, so let's check **Reddit**: https://www.reddit.com/r/UCSD/comments/1kb585n/wooli_replacement_ucsd_sungod_2025/

<p align="center">
  <img src="https://github.com/user-attachments/assets/eed1cba1-6cdc-4d55-a2fa-c5401db8cba4" alt="Reddit post comment with the same hashtag"/>
</p>

So we found an account with a username very similar to Piotr’s: https://www.reddit.com/user/suultangamer/ **suultangamer**. There’re several comments about **Wooli** on this account: we know that Piotr was very upset about the situation with Wooli according to Piotr’s Instagram.

<p align="center">
  <img src="https://github.com/user-attachments/assets/9d27701b-1f6d-4095-b0ea-b980c1e5039e" alt="Reddit comments about Wooli"/>
</p>

And there's a post with link to the **original meme** we've already seen on Imgur Piotr's account.

<p align="center">
  <img src="https://github.com/user-attachments/assets/b3e322af-e982-42b1-9963-a3c9ab35f880" alt="Reddit comment with link to meme"/>
</p>

This one meme: https://i.imgur.com/kUcZxM5.jpeg

<p align="center">
  <img src="https://github.com/user-attachments/assets/2086ccd5-702b-47ed-809a-cf2c6d6fe975" alt="Original meme about Grok"/>
</p>

And here's the twist. If you remember, this imgur post was called "my original meme", and we can see the caption "imgflip.com" in the bottom left corner. So **this meme could also be googled**.

A less obvious way (in my opinion) to find Piotr's Reddit account googling link to the meme from the imgur post:

<p align="center">
  <img src="https://github.com/user-attachments/assets/28896d68-289f-4847-9173-5ac23e910e10" alt="Googling link to the meme from the imgur post"/>
</p>

A more obvious way (but still less obv than using hashtag): use google lens for the meme from the imgur post. It’s important to refocus google lens so the subscription from meme can be recognized by google lens also:

<p align="center">
  <img src="https://github.com/user-attachments/assets/ebb74213-7691-4a91-b28d-322b525cc435" alt="Googling the meme via Google Lens"/>
</p>

And that's how we could find the same suultangamer account: https://www.reddit.com/r/ExplainTheJoke/comments/1kf41s4/i_dont_get_it/. Then we could look for the hashtag and so we have Insta. The same thing, but reversed. Pretty comfortable.

<p align="center">
  <img src="https://github.com/user-attachments/assets/334907b7-3982-405d-b05e-a975a66c75b1" alt="Comment on Reddit about meme"/>
</p>

Anyway, there’s one more post on Reddit: https://www.reddit.com/r/UCSDclassifieds/comments/1kdgojq/free_ditty_party_ticket/

<p align="center">
  <img src="https://github.com/user-attachments/assets/6c816db2-1ab7-4133-ab60-1a8dc9127079" alt="Reddit post about selling ticket"/>
</p>

Selling ticket, etc. With a **QR code**. It happens that a person is ready to give a ticket to the first person who writes, but then they usually send the ticket to the first person in some personal message, and do not post the QR so that the first one who scans it at the entrance will pass, it is quite risky. Well, let's scan this QR code too.

<p align="center">
  <img src="https://github.com/user-attachments/assets/9d359461-aee5-453e-8baa-fe53b3b79d55" alt="Scanned output of QR"/>
</p>

We get **the Plumeria link**: https://goplumeria.com/date/lY0E7CAyyLSpNhz41eCn Let's visit it.

<p align="center">
  <img src="https://github.com/user-attachments/assets/61bd2077-c035-4f40-be99-dbea285bcc39" alt="Site preview"/>
</p>

Oh, so it was an invitation to a date. May 4th. In some city. Even with some ideas for the date.

<p align="center">
  <img src="https://github.com/user-attachments/assets/882b36b6-fd3f-468d-bbf6-0743d0884e6f" alt="Date ideas"/>
</p>

If we google these places, we will find that they’re all located in the same city:

<p align="center">
  <img src="https://github.com/user-attachments/assets/4108f4f8-bff4-41dc-b013-28a8d7c3a5e9" alt="Googling some places"/>
</p>

They are all located in Houston. Let's check the spelling via wikipedia:

<p align="center">
  <img src="https://github.com/user-attachments/assets/eae576f2-f7df-4f5f-906f-ff859747927b" alt="Wikipedia Houston page"/>
</p>

The last flag for May 4th or Day 1: **Houston**.

## Conclusion

It was a pretty cool OSINT: diverse, with the need to use different approaches to find information, quite realistic. Here is the mindmap that my team and I made during the competition, it looks like a person-search-board from the movie, quite funny:

<p align="center">
  <img src="https://github.com/user-attachments/assets/54350a51-0c2d-4781-aafb-432c29cbb8fd" alt="Mindmap for Piotr"/>
</p>
