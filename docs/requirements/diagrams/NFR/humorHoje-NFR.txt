{
  "actors": [],
  "orphans": [
    {
      "id": "f87f3440-84b6-4ce0-af3b-b01fab0d9c46",
      "text": "Segurança",
      "type": "nfr.NFR",
      "x": 1083,
      "y": 155
    },
    {
      "id": "5edf8ec7-6285-4cf4-b655-d142beef72ae",
      "text": "Confiabilidade",
      "type": "nfr.NFR",
      "x": 149,
      "y": 149
    },
    {
      "id": "04e6bc30-3a4d-4b8c-8c37-46f58f08865f",
      "text": "Usabilidade",
      "type": "nfr.NFR",
      "x": 545,
      "y": 231
    },
    {
      "id": "997a7077-7049-43ad-afa5-ba1fe95bec37",
      "text": "Registrar Humor de Forma Offline",
      "type": "nfr.Operationalization",
      "x": 77,
      "y": 475
    },
    {
      "id": "6e801c4a-26ad-412f-a170-50d24d0bc7f3",
      "text": "Fazer Backup Diário",
      "type": "nfr.Operationalization",
      "x": 218,
      "y": 268
    },
    {
      "id": "a928940a-eb8c-4bb1-b2b3-34c5f832f51b",
      "text": "Criptografar Dados",
      "type": "nfr.Operationalization",
      "x": 977,
      "y": 417
    },
    {
      "id": "929fc96a-abe3-4717-ac19-2a995f49841f",
      "text": "Comunicação segura (TLS 1.2+) ",
      "type": "nfr.Operationalization",
      "x": 1174,
      "y": 396
    },
    {
      "id": "de83ee86-28f4-4915-a1c8-2af81d05c542",
      "text": "Interface Intuitiva (UX/UI)",
      "type": "nfr.NFR",
      "x": 353,
      "y": 470
    },
    {
      "id": "09bddb8d-2fb2-4610-9ec7-fc0838a68911",
      "text": "Eficiência na primeira tarefa (<1min)",
      "type": "nfr.NFR",
      "x": 493,
      "y": 529
    },
    {
      "id": "55590753-ce61-4cb6-8ffe-e5778be030d6",
      "text": "Comunicação clara",
      "type": "nfr.NFR",
      "x": 758,
      "y": 402
    },
    {
      "id": "58d4a68b-86e6-4624-a42e-2828f82b58f1",
      "text": "Design Responsivo",
      "type": "nfr.NFR",
      "x": 646,
      "y": 486
    }
  ],
  "dependencies": [],
  "links": [
    {
      "id": "3e3ec763-bf3e-4f49-82bb-3138355e498b",
      "type": "nfr.AndRefinementLink",
      "source": "997a7077-7049-43ad-afa5-ba1fe95bec37",
      "target": "5edf8ec7-6285-4cf4-b655-d142beef72ae"
    },
    {
      "id": "38ff1194-1b0b-48eb-b529-e4874ab98b33",
      "type": "nfr.AndRefinementLink",
      "source": "6e801c4a-26ad-412f-a170-50d24d0bc7f3",
      "target": "5edf8ec7-6285-4cf4-b655-d142beef72ae"
    },
    {
      "id": "c56243dd-aee3-42bd-bbf8-ad1e7492e733",
      "type": "nfr.AndRefinementLink",
      "source": "de83ee86-28f4-4915-a1c8-2af81d05c542",
      "target": "04e6bc30-3a4d-4b8c-8c37-46f58f08865f"
    },
    {
      "id": "9ad6fb86-29d4-43cd-ac76-645bcac680b2",
      "type": "nfr.AndRefinementLink",
      "source": "09bddb8d-2fb2-4610-9ec7-fc0838a68911",
      "target": "04e6bc30-3a4d-4b8c-8c37-46f58f08865f"
    },
    {
      "id": "7e0d83bd-2490-4f6c-a091-d254fb0c8d3e",
      "type": "nfr.AndRefinementLink",
      "source": "55590753-ce61-4cb6-8ffe-e5778be030d6",
      "target": "04e6bc30-3a4d-4b8c-8c37-46f58f08865f"
    },
    {
      "id": "b56da925-2d07-41fb-b4b9-dcc84e61b258",
      "type": "nfr.AndRefinementLink",
      "source": "58d4a68b-86e6-4624-a42e-2828f82b58f1",
      "target": "04e6bc30-3a4d-4b8c-8c37-46f58f08865f"
    },
    {
      "id": "e820b622-73ee-447f-9919-4fe1a11b95e1",
      "type": "nfr.AndRefinementLink",
      "source": "a928940a-eb8c-4bb1-b2b3-34c5f832f51b",
      "target": "f87f3440-84b6-4ce0-af3b-b01fab0d9c46"
    },
    {
      "id": "691117ef-c54c-474a-8c3a-cc2a22c72fb9",
      "type": "nfr.AndRefinementLink",
      "source": "929fc96a-abe3-4717-ac19-2a995f49841f",
      "target": "f87f3440-84b6-4ce0-af3b-b01fab0d9c46"
    },
    {
      "id": "243b96d7-28d5-4da9-8413-b06f29b92d0a",
      "type": "nfr.CorrelationLink",
      "source": "f87f3440-84b6-4ce0-af3b-b01fab0d9c46",
      "target": "04e6bc30-3a4d-4b8c-8c37-46f58f08865f",
      "label": "– –"
    },
    {
      "id": "aa0d0544-52bf-416f-8d4b-5dd88ea44fdf",
      "type": "nfr.ContributionLink",
      "source": "997a7077-7049-43ad-afa5-ba1fe95bec37",
      "target": "04e6bc30-3a4d-4b8c-8c37-46f58f08865f",
      "label": "+"
    },
    {
      "id": "0ba85333-1776-46f6-b91c-ec3b7c3c82bd",
      "type": "nfr.ContributionLink",
      "source": "6e801c4a-26ad-412f-a170-50d24d0bc7f3",
      "target": "f87f3440-84b6-4ce0-af3b-b01fab0d9c46",
      "label": "++"
    }
  ],
  "display": {
    "997a7077-7049-43ad-afa5-ba1fe95bec37": {
      "width": 138.5863800048828,
      "height": 70.78462219238281
    },
    "6e801c4a-26ad-412f-a170-50d24d0bc7f3": {
      "width": 104.58953857421875,
      "height": 69.28474426269531
    },
    "a928940a-eb8c-4bb1-b2b3-34c5f832f51b": {
      "width": 117.58837890625,
      "height": 79.78245544433594
    },
    "929fc96a-abe3-4717-ac19-2a995f49841f": {
      "width": 163.58377075195312,
      "height": 83.78157043457031
    },
    "de83ee86-28f4-4915-a1c8-2af81d05c542": {
      "width": 127.58737182617188,
      "height": 76.28343200683594
    },
    "09bddb8d-2fb2-4610-9ec7-fc0838a68911": {
      "width": 107.58926391601562,
      "height": 73.28388977050781
    },
    "55590753-ce61-4cb6-8ffe-e5778be030d6": {
      "width": 112.58883666992188,
      "height": 72.28407287597656
    },
    "58d4a68b-86e6-4624-a42e-2828f82b58f1": {
      "width": 104.58964538574219,
      "height": 64.28602600097656
    },
    "243b96d7-28d5-4da9-8413-b06f29b92d0a": {
      "vertices": [
        {
          "x": 884,
          "y": 265
        }
      ]
    },
    "0ba85333-1776-46f6-b91c-ec3b7c3c82bd": {
      "vertices": [
        {
          "x": 652,
          "y": 145
        }
      ]
    }
  },
  "tool": "dsm3-goals",
  "metamodelVersion": "1.0",
  "saveDate": "Thu, 17 Jul 2025 17:28:10 GMT",
  "diagram": {
    "width": 2217,
    "height": 1300,
    "name": "Diário de Humor e Bem-Estar - Grafo SIG de 3 NFR",
    "customProperties": {
      "Description": "Grafo SIG de 3 Requisitos Não Funcionais da aplicação Diário de Humor e Bem-Estar da matéria de Engenharia de Requisitos do curso de Engenharia de Software da UFRN."
    }
  }
}