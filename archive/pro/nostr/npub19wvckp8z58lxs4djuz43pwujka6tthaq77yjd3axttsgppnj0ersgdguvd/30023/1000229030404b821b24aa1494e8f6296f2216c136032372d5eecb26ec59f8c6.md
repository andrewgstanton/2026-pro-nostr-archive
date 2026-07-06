# Digital Independence Day

Today America celebrates its 250th birthday.

Two hundred and fifty years ago, the Founding Fathers signed one of the most consequential documents in human history. The Declaration of Independence wasn't simply about separating from Great Britain. It was about something much deeper: who should have the authority to govern?

As I thought about that today, it occurred to me that we're beginning to wrestle with similar questions in the digital world.

Not about governments, but about software.

Over the last year, actually ever since I started building Continuum, I've written quite a bit about digital sovereignty. This week, however, I realized I needed to refine what I meant by that.

## Digital Dependence

Much of our digital lives now exist inside platforms that we don't control.

Our identities, writing, photos, relationships—even our memories—are often entrusted to someone else's application or someone else's servers.

Most of the time that's perfectly fine.

Until it isn't.

Platforms change; companies get acquired; services shut down.

(Anyone remember MySpace?)

When that happens, we often discover just how dependent we've become.

## What Changed?

Earlier this week I migrated Continuum's archive from GitHub Pages to Cloudflare Pages.

A day later I built the first version of Continuum Media using Cloudflare R2.

If you had asked me a year ago whether I would use Cloudflare as part of Continuum, I probably would have hesitated. After all, wasn't I trying to build sovereign software?

But after making those changes, I realized I had been asking the wrong question.

The interesting part wasn't that I changed providers.

The interesting part was how little else had to change.

The archive structure stayed the same.

The publishing workflow stayed the same.

The URLs stayed (mostly) the same.

In fact, Continuum itself hardly changed at all.

The providers changed but not the architecture.

That's when it finally clicked.

## Owning the Architecture

When people hear the word *sovereignty*, they often think it means self-hosting everything: running your own servers, owning every piece of hardware, and never trusting anyone else's infrastructure.

There's certainly value in that approach, and I hope Continuum eventually makes that easier than ever.

But I don't think that's actually the objective.

Technology changes. Companies come and go (anyone remember MySpace?), protocols evolve, and eventually something better comes along. Good software should expect that instead of pretending today's infrastructure will still be the right choice ten years from now.

If I decide next year that I want to replace Cloudflare R2 with Blossom, Amazon S3, or my own object storage, I shouldn't have to redesign Continuum to make that happen. The Media Library should continue doing exactly what it does today, and the article editor shouldn't care where an image ultimately lives. As an author, I should simply upload the image and continue writing.

That's what good architecture gives you.

It gives you the freedom to replace the implementation without rebuilding the application.

## A Different Definition

This week changed the way I think about digital sovereignty.

I don't think it's primarily about owning every piece of infrastructure.

I think it's about owning the architecture.

If you own the architecture, you're free to change the infrastructure.

That's exactly what happened this week.

I moved from GitHub Pages to Cloudflare Pages.

I built Continuum Media on Cloudflare R2.

Neither decision required me to rethink Continuum because those providers were never meant to define the software in the first place.

They're implementation details.

Two hundred and fifty years after the Declaration of Independence, I find myself thinking about independence in a different context.

Political independence matters.

But I also think we should be asking what digital independence ought to look like.

For me, it isn't about eliminating every dependency.

It's about making sure no dependency becomes permanent.

If I can change providers without changing my identity, my content, or the way I work, then I haven't given up control.

I've preserved it.

I think that's a goal worth building toward.