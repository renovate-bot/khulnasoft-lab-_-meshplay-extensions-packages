# Meshplay Design Embed Package

Meshplay Design Embedding allows you to export a design in a format that can be integrated into websites, blogs, or platforms supporting HTML, CSS, and JavaScript. This embedded version offers an interactive representation of the design, simplifying sharing with infrastructure stakeholders.

## meshplay-design-embed react component

this component is meant to facilate the usage of meshplay embeddings inside react and its frameworks

usage :

```
import MeshplayDesignEmbed from '@khulnasoft/meshplay-design-embed'


function Design() {
  return (
    <>

      <div>
        <MeshplayDesignEmbed
          embedScriptSrc="embedded-design-embed1.js"  // path to the embed script
          embedId="embedded-design-a3d3f26e-4366-44e6-b211-1ba4e1a3e644" // id of the embedding
        />
      </div>
    </>
  );
}

```

Learn more about [embedding Meshplay Designs](https://docs.khulnasoft.com/meshmap/designer/export-designs/#exporting-as-embedding).
