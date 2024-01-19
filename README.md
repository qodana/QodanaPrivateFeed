## Example of using Qodana for .NET with private NuGet feed

To use private NuGet feeds in Qodana for .NET, you can add the following environmental variables to your job:
* `QODANA_NUGET_URL=URL` - your NuGet feed url, e.g. `https://nuget.pkg.github.com/brichbash/index.json`
* `QODANA_NUGET_USER=LOGIN`
* `QODANA_NUGET_PASSWORD=PASSWORD`

See the example configuration for GitHub Actions in `./.github/workflows/code-quality.yml`