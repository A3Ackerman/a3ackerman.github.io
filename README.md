# Notes to self

To render to PDF, preserving parsability use: 
`prince http://localhost:1313 --page-size=A2 --page-margin=0 -o ~/desktop/AAckerman_resume.pdf`
Make sure that the contacts partial has real HTML in it (Prince can't compute css as well as chrome does)

### Viewing

To view your site, execute the following: 

    $ hugo server

and go to `localhost:1313` in your browser.

### Building

To generate your site in the `public` folder, execute the following:

    $ hugo

within the root of your project.


# Credits

Thanks to Xiaoying Riley for developing [DevResume](//github.com/xriley/DevResume-Theme), and Cowboysmall for porting it to Hugo!


## License

This template is 100% FREE as long as you keep the footer attribution link. You do not have the rights to resell, 
sublicense or redistribute (even for free) the template on its own or as a separate attachment from any of your work.
If you’d like to use this template without the footer attribution link, you can buy the 
[commercial license](https://themes.3rdwavemedia.com/bootstrap-templates/resume/devresume-free-bootstrap-4-resume-cv-template-for-developers/)

You may change the "Ported for..." line by adding the following to the end of `config.toml`
    
    [params.footer]
        copyright = ""

