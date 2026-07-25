# Notes

## Questions

- What is "metadata_expire=6h" do?

Once the cached metadata is older than 6 hours, DNF considers it expired and may refresh it during a future operation.

- What does "mirrorlist" do?

mirrorlist tells DNF to check the URL and get a list of mirror servers that provide this repository.

- Does the order of configuration options inside a .repo file matter?

No, it doesn't.
