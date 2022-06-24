<!-- @format -->

<template>
  <v-treeview :items="items"></v-treeview>
</template>
<script>
export default {
  name: "TreeviewComponent",
  data: () => ({
    items: [
      {
        id: 1,
        name: "Tamilnadu",
        children: [
          {
            id: 2,
            name: "Preset",   
            children: [
              {
                id: 3,
                name: "Default",
                children: [{ id: 4, name: "Defa" }],
              },
            ],
          },
          {
            id: 5,
            name: "Ariyalur",
            children: [
              {
                id: 6,
                name: "Preset",
                children: [
                  {
                    id: 7,
                    name: "Default",
                  },
                ],
              },
              {
                id: 8,
                name: "Responses",
                children: [{ id: 9, name: "11.1401 | 79.0786" }],
              },
            ],
          },
          {
            id: 10,
            name: "Chengalpattu",
            children: [
              {
                id: 11,
                name: "Preset",
                children: [
                  {
                    id: 12,
                    name: "Default",
                  },
                ],
              },
              {
                id: 13,
                name: "Responses",
                children: [{ id: 14, name: "12.6819 | 79.9888" }],
              },
            ],
          },
          {
            id: 15,
            name: "Chennai",
            children: [
              {
                id: 16,
                name: "Preset",
                children: [
                  {
                    id: 17,
                    name: "Default",
                  },
                ],
              },
              {
                id: 18,
                name: "Responses",
                children: [{ id: 19, name: "13.0827 | 80.2707" }],
              },
            ],
          },
          {
            id: 20,
            name: "Coimbatore",
            children: [
              {
                id: 21,
                name: "Preset",
                children: [
                  {
                    id: 22,
                    name: "Default",
                  },
                ],
              },
              {
                id: 23,
                name: "Responses",
                children: [{ id: 24, name: "11.0168 | 76.9558" }],
              },
            ],
          },
          {
            id: 25,
            name: "Cuddalore",
            children: [
              {
                id: 26,
                name: "Preset",
                children: [
                  {
                    id: 27,
                    name: "Default",
                  },
                ],
              },
              {
                id: 28,
                name: "Responses",
                children: [{ id: 18, name: "11.748 | 79.7714" }],
              },
            ],
          },
          {
            id: 11,
            name: "Dharmapuri",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "12.1211 | 78.1582" }],
              },
            ],
          },
          {
            id: 11,
            name: "Dindigul",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "10.3624 | 77.9695" }],
              },
            ],
          },
          {
            id: 11,
            name: "Erode",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "11.341 | 77.7172" }],
              },
            ],
          },
          {
            id: 11,
            name: "Kallakuruchi",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "11.7384 | 78.9639" }],
              },
            ],
          },
          {
            id: 11,
            name: "Kancheepuram",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "12.8185 | 79.6947" }],
              },
            ],
          },
          {
            id: 11,
            name: "Karur",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "10.9601 | 78.0766" }],
              },
            ],
          },
          {
            id: 11,
            name: "Krishnagiri",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "12.5266 | 78.215" }],
              },
            ],
          },
          {
            id: 11,
            name: "Madurai",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "9.9252 | 78.1198" }],
              },
            ],
          },
          {
            id: 11,
            name: "Mayiladuthurai",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "11.1018 | 79.6526" }],
              },
            ],
          },
          {
            id: 11,
            name: "Nagapattinam",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "10.7672 | 79.8449" }],
              },
            ],
          },
          {
            id: 11,
            name: "Kanyakumari",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "8.0883 | 77.5385" }],
              },
            ],
          },
          {
            id: 11,
            name: "Namakkal",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "11.2194 | 78.1678" }],
              },
            ],
          },
          {
            id: 11,
            name: "Perambalur",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "11.2342 | 78.8807" }],
              },
            ],
          },
          {
            id: 11,
            name: "Pudukottai",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "10.3833 | 78.8001" }],
              },
            ],
          },
          {
            id: 11,
            name: "Ramanathpuram",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "9.3639 | 78.8395" }],
              },
            ],
          },
          {
            id: 11,
            name: "Ranipet",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "12.932063 | 79.333466" }],
              },
            ],
          },
          {
            id: 11,
            name: "Salem",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "11.6643 | 78.146" }],
              },
            ],
          },
          {
            id: 11,
            name: "Sivagangai",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "9.8433 | 78.4809" }],
              },
            ],
          },
          {
            id: 11,
            name: "Tenkasi",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "8.9564 | 77.3152" }],
              },
            ],
          },
          {
            id: 11,
            name: "Thanjavur",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "10.787 | 79.1378" }],
              },
            ],
          },
          {
            id: 11,
            name: "Theni",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "10.0079 | 77.4735" }],
              },
            ],
          },
          {
            id: 11,
            name: "Thiruvallur",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "13.1231 | 79.912" }],
              },
            ],
          },
          {
            id: 11,
            name: "Thiruvarur",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "10.7661 | 79.6344" }],
              },
            ],
          },
          {
            id: 11,
            name: "Tuticorin",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "8.7642 | 78.1348" }],
              },
            ],
          },
          {
            id: 11,
            name: "Trichirapalli",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "10.7905 | 78.7047" }],
              },
            ],
          },
          {
            id: 11,
            name: "Thirunelveli",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "8.7139 | 77.7567" }],
              },
            ],
          },
          {
            id: 11,
            name: "Tirupathur",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "12.4754 | 78.5855" }],
              },
            ],
          },
          {
            id: 11,
            name: "Tiruppur",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "11.1085 | 77.3411" }],
              },
            ],
          },
          {
            id: 11,
            name: "Tiruvannamalai",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "12.2253 | 79.0747" }],
              },
            ],
          },
          {
            id: 11,
            name: "The Nalgiris",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "11.4916 | 76.7337" }],
              },
            ],
          },
          {
            id: 11,
            name: "Vellore",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "12.9165 | 79.1325" }],
              },
            ],
          },
          {
            id: 11,
            name: "Viluppuram",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "11.9401 | 79.4861" }],
              },
            ],
          },

          {
            id: 11,
            name: "Viridhunagar",
            children: [
              {
                id: 7,
                name: "Preset",
                children: [
                  {
                    id: 8,
                    name: "Default",
                  },
                ],
              },
              {
                id: 12,
                name: "Responses",
                children: [{ id: 18, name: "9.568 | 77.9624" }],
              },
            ],
          },
        ],
      },
    ],
  }),
};
</script>
