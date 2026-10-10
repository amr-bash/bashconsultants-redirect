# bashconsultants-redirect

Redirects `bashconsultants.com` (and `www.bashconsultants.com`) to `https://www.bash-365.com`, keeping the path.

BASH's site lives at `www.bash-365.com` on an Azure Static Web App. `bashconsultants.com` is an older
domain with DNS in Microsoft 365, pointing at GitHub Pages; this repo answers there with a
client-side redirect (`index.html` for `/`, `404.html` for every other path). The domain is verified
to the `amr-bash` GitHub account so no one else can claim it.

Sibling of `amr-bash/bash-365-apex`, which does the same for the bare `bash-365.com`.
