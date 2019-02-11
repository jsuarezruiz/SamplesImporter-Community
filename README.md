# Community Samples for VS4Mac Samples Importer addin

Community samples section for VS4Mac Samples Importer addin. 

### How can I add a sample?

Easy, just send a PR with your sample!. Remember to meet the following requirements:
- Include the sample inside a folder in the root of the repository.
- The folder name should be the name of the sample.
- Inside the sample folder, create a **Screenshots** folder.
- Include the file **Metadata.xml** inside your sample folder.

```
<?xml version="1.0" encoding="utf-8" ?>
<SampleMetadata>
    <Level>Intermediate</Level>
    <Tags>Xamarin.Forms, SkiaSharp</Tags>
    <SupportedPlatforms>Android, iOS</SupportedPlatforms>
    <Gallery>true</Gallery>
    <Brief>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam malesuada arcu id porta consequat. .</Brief>
</SampleMetadata>

```

Or just include the DownloadUrl in the XML file without include the sample code in the repository:

```
<?xml version="1.0" encoding="utf-8" ?>
<SampleMetadata>
    <Level>Intermediate</Level>
    <Tags>Xamarin.Forms, SkiaSharp</Tags>
    <SupportedPlatforms>Android, iOS</SupportedPlatforms>
    <Gallery>true</Gallery>
    <Brief>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam malesuada arcu id porta consequat. .</Brief>
    <DownloadUrl>https://github.com/user/Sample/archive/master.zip</DownloadUrl>
</SampleMetadata>

```

## Copyright and license

Code released under the [MIT license](https://opensource.org/licenses/MIT).