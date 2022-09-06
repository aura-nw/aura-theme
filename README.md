add index.scss to angular.json
{
  "projects": {
    "project-name": {
      "architect": {
        "build": {
          "options": {
            "styles": [
              "./node_modules/aura-network-theme/index.scss",
            ],
          },
        },
      }
    }
  },
}
