
## Welcome to MarkdownPad 2 ##

**MarkdownPad** is a full-featured Markdown editor for Windows.

### Built exclusively for Markdown ###

Enjoy first-class Markdown support with easy access to  Markdown syntax and convenient keyboard shortcuts.

Give them a try:

- **Bold** (`Ctrl+B`) and *Italic* (`Ctrl+I`)
- Quotes (`Ctrl+Q`)
- Code blocks (`Ctrl+K`)
- Headings 1, 2, 3 (`Ctrl+1`, `Ctrl+2`, `Ctrl+3`)
- Lists (`Ctrl+U` and `Ctrl+Shift+O`)

### See your changes instantly with LivePreview ###

Don't guess if your [hyperlink syntax](http://markdownpad.com) is correct; LivePreview will show you exactly what your document looks like every time you press a key.

### Make it your own ###

Fonts, color schemes, layouts and stylesheets are all 100% customizable so you can turn MarkdownPad into your perfect editor.

### A robust editor for advanced Markdown users ###

MarkdownPad supports multiple Markdown processing engines, including standard Markdown, Markdown Extra (with Table support) and GitHub Flavored Markdown.

With a tabbed document interface, PDF export, a built-in image uploader, session management, spell check, auto-save, syntax highlighting and a built-in CSS management interface, there's no limit to what you can do with MarkdownPad.

 ```SQLPL
    Select *
    From 
      (Select dual=1) as Dual
      CROSS APPLY
      ( -- expression "row constructor".  Cette expression introduite par la clause Values
        -- permet de simuler une table virtuelle avec ses rangées.  
      Values 
        (1, 'RangeeTableNumero1')
      , (2, 'RangeeTableNumero1')
      , (3, 'RangeeTableNumero1') 
      ) as TableNumeroUn (Sequence, Valeur)
    GROUP BY i
    ORDER BY 1
 ```

<pre style='color:#000000;background:#ffffff;'><span style='color:#800000; font-weight:bold; '>If</span> Schema_Id<span style='color:#808030; '>(</span><span style='color:#0000e6; '>'Schemas'</span><span style='color:#808030; '>)</span> <span style='color:#800000; font-weight:bold; '>IS</span> <span style='color:#800000; font-weight:bold; '>NULL</span> <span style='color:#800000; font-weight:bold; '>Exec</span> <span style='color:#808030; '>(</span><span style='color:#0000e6; '>'Create Schema Schemas authorization Dbo'</span><span style='color:#808030; '>)</span>
<span style='color:#800000; font-weight:bold; '>Exec</span> f$<span style='color:#808030; '>.</span>DropObj <span style='color:#0000e6; '>'[Schemas].[EnumProd]'</span>
<span style='color:#800000; font-weight:bold; '>Create</span> <span style='color:#800000; font-weight:bold; '>View</span> <span style='color:#808030; '>[</span>Schemas<span style='color:#808030; '>]</span><span style='color:#808030; '>.</span><span style='color:#808030; '>[</span>EnumProd<span style='color:#808030; '>]</span> 
<span style='color:#800000; font-weight:bold; '>As</span>
<span style='color:#800000; font-weight:bold; '>Select</span>  
  AG<span style='color:#808030; '>=</span><span style='color:#800000; font-weight:bold; '>CAST</span><span style='color:#808030; '>(</span><span style='color:#0000e6; '>'AG'</span> <span style='color:#800000; font-weight:bold; '>as</span> nvarchar<span style='color:#808030; '>(</span><span style='color:#008c00; '>10</span><span style='color:#808030; '>)</span><span style='color:#808030; '>)</span>                  <span style='color:#808030; '>,</span> DbAG<span style='color:#808030; '>=</span><span style='color:#0000e6; '>'SchemasAG'</span>
<span style='color:#808030; '>,</span> AX<span style='color:#808030; '>=</span><span style='color:#800000; font-weight:bold; '>CAST</span><span style='color:#808030; '>(</span><span style='color:#0000e6; '>'AX'</span> <span style='color:#800000; font-weight:bold; '>as</span> nvarchar<span style='color:#808030; '>(</span><span style='color:#008c00; '>10</span><span style='color:#808030; '>)</span><span style='color:#808030; '>)</span>                  <span style='color:#808030; '>,</span> DbAX<span style='color:#808030; '>=</span><span style='color:#0000e6; '>'SchemasAX'</span>
<span style='color:#808030; '>,</span> ACHAT<span style='color:#808030; '>=</span><span style='color:#800000; font-weight:bold; '>CAST</span><span style='color:#808030; '>(</span><span style='color:#0000e6; '>'ACHAT'</span> <span style='color:#800000; font-weight:bold; '>as</span> nvarchar<span style='color:#808030; '>(</span><span style='color:#008c00; '>10</span><span style='color:#808030; '>)</span><span style='color:#808030; '>)</span>            <span style='color:#808030; '>,</span> DbACHAT<span style='color:#808030; '>=</span><span style='color:#0000e6; '>'SchemasACHAT'</span>
<span style='color:#808030; '>,</span> DOFIN<span style='color:#808030; '>=</span><span style='color:#800000; font-weight:bold; '>CAST</span><span style='color:#808030; '>(</span><span style='color:#0000e6; '>'DOFIN'</span> <span style='color:#800000; font-weight:bold; '>as</span> nvarchar<span style='color:#808030; '>(</span><span style='color:#008c00; '>10</span><span style='color:#808030; '>)</span><span style='color:#808030; '>)</span>            <span style='color:#808030; '>,</span> DbDOFIN<span style='color:#808030; '>=</span><span style='color:#0000e6; '>'SchemasDOFIN'</span>
<span style='color:#808030; '>,</span> EDU_GROUPE<span style='color:#808030; '>=</span><span style='color:#800000; font-weight:bold; '>CAST</span><span style='color:#808030; '>(</span><span style='color:#0000e6; '>'EDU_GROUPE'</span> <span style='color:#800000; font-weight:bold; '>as</span> nvarchar<span style='color:#808030; '>(</span><span style='color:#008c00; '>10</span><span style='color:#808030; '>)</span><span style='color:#808030; '>)</span>  <span style='color:#808030; '>,</span> DbEDU_GROUPE<span style='color:#808030; '>=</span><span style='color:#0000e6; '>'SchemasEDU_GROUPE'</span>
<span style='color:#808030; '>,</span> GEOBUS<span style='color:#808030; '>=</span><span style='color:#800000; font-weight:bold; '>CAST</span><span style='color:#808030; '>(</span><span style='color:#0000e6; '>'GEOBUS'</span> <span style='color:#800000; font-weight:bold; '>as</span> nvarchar<span style='color:#808030; '>(</span><span style='color:#008c00; '>10</span><span style='color:#808030; '>)</span><span style='color:#808030; '>)</span>          <span style='color:#808030; '>,</span> DbGEOBUS<span style='color:#808030; '>=</span><span style='color:#0000e6; '>'SchemasGEOBUS'</span>
<span style='color:#808030; '>,</span> GPI<span style='color:#808030; '>=</span><span style='color:#800000; font-weight:bold; '>CAST</span><span style='color:#808030; '>(</span><span style='color:#0000e6; '>'GPI'</span> <span style='color:#800000; font-weight:bold; '>as</span> nvarchar<span style='color:#808030; '>(</span><span style='color:#008c00; '>10</span><span style='color:#808030; '>)</span><span style='color:#808030; '>)</span>                <span style='color:#808030; '>,</span> DbGPI<span style='color:#808030; '>=</span><span style='color:#0000e6; '>'SchemasGPI'</span>
<span style='color:#808030; '>,</span> JADE<span style='color:#808030; '>=</span><span style='color:#800000; font-weight:bold; '>CAST</span><span style='color:#808030; '>(</span><span style='color:#0000e6; '>'JADE'</span> <span style='color:#800000; font-weight:bold; '>as</span> nvarchar<span style='color:#808030; '>(</span><span style='color:#008c00; '>10</span><span style='color:#808030; '>)</span><span style='color:#808030; '>)</span>              <span style='color:#808030; '>,</span> DbJADE<span style='color:#808030; '>=</span><span style='color:#0000e6; '>'SchemasJADE'</span>
<span style='color:#808030; '>,</span> PAIE<span style='color:#808030; '>=</span><span style='color:#800000; font-weight:bold; '>CAST</span><span style='color:#808030; '>(</span><span style='color:#0000e6; '>'PAIE'</span> <span style='color:#800000; font-weight:bold; '>as</span> nvarchar<span style='color:#808030; '>(</span><span style='color:#008c00; '>10</span><span style='color:#808030; '>)</span><span style='color:#808030; '>)</span>              <span style='color:#808030; '>,</span> DbPAIE<span style='color:#808030; '>=</span><span style='color:#0000e6; '>'SchemasPAIE'</span>
<span style='color:#808030; '>,</span> PROCURE<span style='color:#808030; '>=</span><span style='color:#800000; font-weight:bold; '>CAST</span><span style='color:#808030; '>(</span><span style='color:#0000e6; '>'PROCURE'</span> <span style='color:#800000; font-weight:bold; '>as</span> nvarchar<span style='color:#808030; '>(</span><span style='color:#008c00; '>10</span><span style='color:#808030; '>)</span><span style='color:#808030; '>)</span>        <span style='color:#808030; '>,</span> DbPROCURE<span style='color:#808030; '>=</span><span style='color:#0000e6; '>'SchemasPROCURE'</span>
<span style='color:#808030; '>,</span> TFP<span style='color:#808030; '>=</span><span style='color:#800000; font-weight:bold; '>CAST</span><span style='color:#808030; '>(</span><span style='color:#0000e6; '>'TFP'</span> <span style='color:#800000; font-weight:bold; '>as</span> nvarchar<span style='color:#808030; '>(</span><span style='color:#008c00; '>10</span><span style='color:#808030; '>)</span><span style='color:#808030; '>)</span>                <span style='color:#808030; '>,</span> DbTFP<span style='color:#808030; '>=</span><span style='color:#0000e6; '>'SchemasTFP'</span>
</pre>
<!--Created using ToHtml.com on 2018-10-25 23:21:01 UTC -->