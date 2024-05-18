# Combined Balena Sound and LiFePO4wered-Pi Project Using Git Submodules

To Build and Deploy:

`balena login`

then:

`balena push balena-sound-lifepo4 --registry-secrets .\secrets.yml

To update each project (git submodule), run in root of project:
`git submodule update --remote --merge`
