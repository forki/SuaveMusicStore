# Page not found

You might have noticed, that when you try to access a missing resource (for example entering album details url with arbitrary album id) then no response is sent.
In order to fix that, let's add a "Page Not Found" handler to our main `choose` WebPart as a last resort:

==> App.fs:`let webPart`

the `View.notFound` can then look like:

==> View.fs:`let notFound`

