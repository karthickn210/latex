# latex
latex installination for ubuntu and linux users

LaTeX is a document markup language and a text preparation system to create documents. LaTeX is recommended to create technical or scientific articles, papers, reports, books and other documents like PhDs

# 1. OPEN YOUR TERMINAL
     
     ctrl+alt+t
      
# 2. INSTALL TEX LIVE
      TeX Live is a TeX distribution to get up and running with the TeX document production system. To install it, once you're in the terminal, enter the following command:
      
      sudo apt-get install texlive-full
      
      Relax and have coffee
      
# 3. INSTALL TEXMAKER
      Now you need a text editor. I recommend using a specific editor for LaTeX. There are many text editors for LaTeX on the Internet as Kile, TeXworks, JLatexEditor, Gedit LaTeX Plugin, etc. My favorite text editor for Latex is Texmaker. Texmaker is a cross-platform open source LaTeX editor. To install it, go to the Ubuntu or Debian terminal and enter the following command:
      
     sudo apt-get install texmaker 
     
     In a few minutes you'll have installed Texmaker.
     
# 4. CREATE YOUR FIRST DOCUMENT
      To check that everything is working properly, create a LaTeX blank document. Open Texmaker and click on File, New. Then write the following code:
      
      \documentclass{article}
      \begin{document}
          Hello, world!
      \end{document}
      
      Now save the document as a 'tex' file going to File, Save. Finally, compile the document clicking on Tools, PDFLaTeX. Make sure the 'pdf' file has been created and it's working. And that's it! You've created your first LaTeX document!
      
      
