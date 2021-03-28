#ExpressionEngine & Markdown

Ever wanted to have ExpressionEngine pull content from Markdown files directly into entries, and have the site update when changes are made to the markdown-files? Read on...

I asked the following question on the ExpressionEngine Forums a few months ago:

> Hi all,
>
> I'm writing a lot of ExpressionEngine related guides and content at the moment in Typora (a great markdown editor). Right now I have to copy/paste the text from Typora, into EE entries with a markdown formatted textarea field, and then publish.
>
> This works great, but also means that, in order to only have one version of the text, any changes will have to be made in Typora first, and then copied over to EE — even small typo-fixes and such.
>
> Is there any way I could have the markdown files on the server, and have them auto-update the entries? Exactly like Templates work, where you first create a template in EE, it's then available on the server as a file, and any changes made to this file is reflected on the site when you save.
>
> Does such a system exist already? If not, perhaps an add-on could be made, or it could be a feature of ExpressionEngine in the future?

Read the rest of my post and the replies, [on the ExpressionEngine Forums here...](https://expressionengine.com/forums/topic/252997/import-markdown-files-as-entries-from-the-server)

The general consensus was that this was a great idea, but no add-on with such functionality existed at the moment.

In the following months I thought about this a lot, and since I'm a web-developer and not a coder (not enough of a coder anyway) I couldn't created an add-on myself. But some solution had to exist to make this possible — and it did!

After a lot of trial and error, I've found the following solution that works pretty well, after you set it up.