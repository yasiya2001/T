{
  "name": "@dark-yasiya/baileys",
  "version": "1.0.7",
  "description": "Baileys with the WhatsApp Web API using WebSocket.",
  "keywords": [
    "darkyasiya",
    "baileys",
    "interactive",
    "whatsapp",
    "whatsapp-bot"
  ],
  "homepage": "https://github.com/DarkYasiyaNew",
  "repository": {
    "url": "git@github.com:WhiskeySockets/Baileys.git"
  },
  "license": "MIT",
  "author": "DarkYasiya",
  "main": "lib/index.js",
  "types": "lib/index.d.ts",
  "files": [
    "lib/**/*",
    "WAProto/**/*"
  ],
  "scripts": {
    "test": "jest"
  },
  "dependencies": {
    "@adiwajshing/keyed-db": "^0.2.4",
    "@cacheable/node-cache": "1.5.3",
    "@hapi/boom": "^9.1.3",
    "async-mutex": "^0.5.0",
    "audio-decode": "^2.2.2",
    "axios": "^1.12.1",
    "cache-manager": "^5.7.6",
    "chalk": "^4.1.2",
    "fflate": "^0.8.2",
    "gradient-string": "^3.0.0",
    "libsignal": "npm:@meta.inc/libsignal@*",
    "link-preview-js": "^3.0.14",
    "lodash": "^4.17.21",
    "lru-cache": "^11.1.0",
    "music-metadata": "^7.12.3",
    "pino": "^9.6",
    "protobufjs": "^7.2.4",
    "qrcode-terminal": "^0.12.0",
    "ws": "^8.13.0"
  },
  "devDependencies": {
    "@types/jest": "^29.5.14",
    "@types/node": "^16.0.0",
    "@types/ws": "^8.0.0",
    "@whiskeysockets/eslint-config": "^1.0.0",
    "conventional-changelog-cli": "^2.2.2",
    "eslint": "^9.38.0",
    "jest": "^30.1.1",
    "jimp": "^0.22.12",
    "json": "^11.0.0",
    "link-preview-js": "^3.0.5",
    "open": "^8.4.2",
    "release-it": "^15.10.3",
    "ts-jest": "^29.4.1",
    "ts-node": "^10.8.1",
    "typedoc": "^0.27.9",
    "typedoc-plugin-markdown": "4.4.2",
    "typescript": "^5.8.2"
  },
  "peerDependencies": {
    "jimp": "^0.22.12"
  },
  "peerDependenciesMeta": {
    "jimp": {
      "optional": true
    }
  },
  "packageManager": "yarn@1.22.19",
  "engines": {
    "node": ">=20.0.0"
  },
  "directories": {
    "lib": "lib"
  }
}
