pandoc Integrazione.md -o Integrazione.html -s --toc \
 --toc-depth=3 \
 --metadata title="Integrazione" \
 --metadata author="Matilde D'Antino" \
 -c https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/5.5.1/github-markdown.min.css \
 -H <(cat << 'EOF'

<style>
  body { 
    max-width: 980px; 
    margin: 0 auto; 
    padding: 45px; 
    background: #f6f8fa; 
  }
  .markdown-body { 
    background: white; 
    padding: 45px; 
    border-radius: 6px; 
    box-shadow: 0 1px 3px rgba(0,0,0,0.12);
  }
  
  /* FIX IMMAGINI - NON SBORDANO MAI */
  img { 
    max-width: 100% !important;
    width: auto !important;
    height: auto !important;
    display: block;
    margin: 20px auto;
    border-radius: 6px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  }
  
  /* Immagini più piccole per la stampa */
  @media print {
    body { 
      background: white; 
      max-width: 100%;
      padding: 2cm;
    }
    .markdown-body { 
      box-shadow: none; 
      padding: 0;
    }
    img { 
      max-width: 90% !important;
      max-height: 500px !important;
      page-break-inside: avoid;
      page-break-after: auto;
    }
  }
  
  h1 { 
    border-bottom: 2px solid #0969da; 
    padding-bottom: 0.3em;
    color: #0969da;
    page-break-after: avoid;
  }
  h2 {
    border-bottom: 1px solid #d8dee4;
    padding-bottom: 0.3em;
    margin-top: 24px;
    page-break-after: avoid;
  }
  
  #TOC {
    background-color: #f6f8fa;
    padding: 20px;
    border-radius: 6px;
    margin-bottom: 30px;
  }
  #TOC ul {
    list-style: none;
    padding-left: 20px;
  }
  #TOC > ul {
    padding-left: 0;
  }
  #TOC a {
    text-decoration: none;
    color: #0969da;
  }
  
  code {
    background-color: #f6f8fa;
    padding: 0.2em 0.4em;
    border-radius: 3px;
    font-size: 0.9em;
  }
  
  pre {
    background-color: #f6f8fa;
    padding: 16px;
    border-radius: 6px;
    overflow-x: auto;
  }
  
  table {
    border-collapse: collapse;
    width: 100%;
    margin: 1em 0;
  }
  th, td {
    border: 1px solid #d0d7de;
    padding: 8px 12px;
    text-align: left;
  }
  th {
    background-color: #f6f8fa;
    font-weight: 600;
  }
</style>

EOF
)

open Integrazione.html
