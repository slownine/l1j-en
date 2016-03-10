# Introduction #

l1j-en is currently being revived and brought back up to date.  I'll edit the other wiki pages later on, but since work is just now being started I made this new document to list my new goals.


# Goals #

  * bring l1j-en up to date to support the latest US live client.  Whatever US live dies with, I want l1j-en to 100% support, but I'm stopping there.  If we ever decide to go further and support clients from other areas I believe the project should be forked or maybe another branch started within this same project. So really this is an entire new page mainly just to make the point that I'm not going to be working on supporting asian clients, at least not with l1j-en anytime in the near future.  With US live dying I think its a perfect opportunity to get l1j-en up to date, fully stable, and fully functional since we won't have to chase down new features with client updates ever again.

  * With the above said, I think I may finally break code compatibility with l1j-jp in order to improve the performance and reliability of our server.  Since we'll be at a feature freeze once we're caught up with the US live, we won't have any need of future merges with l1j-jp(2), so I can finally redo some of the threading and networking without having to worry about being compatible with them.  So in short, a code overhaul of sorts once we're up and running with a focus on stability and performance.

  * Customizations galore.  I want to code in several non live like customizations, but have them as configurable options to activate or not.  That way the code base can be run to mimic live as closely as possible, or server admins can enable certain extras if they wish.  Best of both worlds.  I'm hoping other server admins can even contribute some of these extras.