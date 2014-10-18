PFI (Port Forward Interceptor)
=====

This tool sets up TCP port forward but it intercepts
the traffic and allows you to edit it via a GUI or automatically
via a plugin system. Use it to intercept and modify TCP traffic in flight.
Use it combined with tools like sslmitm and sslstrip to do other useful things.

See the "screenshots" directories for what the UI looks like.

The UI is done entitely with stuff that Python bundles with, there should
be no need to install additional Python modules to make this work. (hence
why it was done with crappy old Tk and not something new and nice like Wx)


