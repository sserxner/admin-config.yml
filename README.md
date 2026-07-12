backend:
  name: github
  repo: sserxner/halfspacefc
  branch: main

media_folder: "images"

collections:
  - name: "rankings"
    label: "Rankings"
    files:
      - label: "Best of the Century"
        name: "century"
        file: "_data/century.json"
        fields:
          - label: "Players"
            name: "players"
            widget: "list"
            fields:
              - { label: "Name", name: "name", widget: "string" }
              - { label: "Detail", name: "detail", widget: "string" }
              - { label: "Note", name: "note", widget: "text" }
      - label: "Best Right Now"
        name: "now"
        file: "_data/now.json"
        fields:
          - label: "Players"
            name: "players"
            widget: "list"
            fields:
              - { label: "Name", name: "name", widget: "string" }
              - { label: "Detail", name: "detail", widget: "string" }
              - { label: "Note", name: "note", widget: "text" }
      - label: "Best Managers — 21st Century"
        name: "managers_century"
        file: "_data/managers_century.json"
        fields:
          - label: "Managers"
            name: "players"
            widget: "list"
            fields:
              - { label: "Name", name: "name", widget: "string" }
              - { label: "Detail", name: "detail", widget: "string" }
              - { label: "Note", name: "note", widget: "text" }
      - label: "Best Managers — Current"
        name: "managers_current"
        file: "_data/managers_current.json"
        fields:
          - label: "Managers"
            name: "players"
            widget: "list"
            fields:
              - { label: "Name", name: "name", widget: "string" }
              - { label: "Detail", name: "detail", widget: "string" }
              - { label: "Note", name: "note", widget: "text" }# admin-config.yml
