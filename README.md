# taleemboard.app
import React from "react";

// ─── COMPLETE SLO DATABASE ────────────────────────────────────────────────────
export const DB = {
  English: {
    color: "#1a56a0",
    light: "#dbeafe",
    emoji: "📖",
    desc: "12 chapters · Reading, Grammar, Writing, Speaking",
    lessonTypes: [
      "Grammar",
      "Reading & Comprehension",
      "Writing",
      "Vocabulary",
      "Speaking & Listening",
    ],
    chapters: [
      {
        id: "e1",
        name: "Ch.1 — Celebrations & Kindness",
        align: "STRONG",
        g2: "Get to Know Me!",
        g3: "Kind Hearts and Sharing Stars",
        g2SLOs: [
          "Listen and respond to a partner during a paired introduction",
          "Use formal and informal greetings correctly",
          "Read with correct pronunciation",
          "Identify proper nouns and capitalization",
          "Use articles a, an, the correctly",
          "Write a short thank-you note",
        ],
        g3SLOs: [
          "Listen in a group circle and respond respectfully",
          "Share a personal experience using full sentences",
          "Identify punctuation in reading",
          "Classify nouns and descriptive words",
          "Write 3–4 sentences about kindness",
        ],
      },
    ],
  },

  Urdu: {
    color: "#6d28d9",
    light: "#ede9fe",
    emoji: "📚",
    desc: "18 chapters · قرأت، قواعد، تحریر، تفہیم",
    lessonTypes: [
      "قرأت / Recitation",
      "لغت / Vocabulary",
      "قواعد / Grammar",
      "تفہیم / Comprehension",
      "تحریر / Writing",
    ],
    chapters: [
      {
        id: "u1",
        name: "باب ۱ — حمد",
        align: "★★★★★",
        g2: "میری صبح",
        g3: "حمد — Praise of Allah",
        g2SLOs: [
          "Recite a short nazm with correct pronunciation",
          "Learn 5 vocabulary words",
          "Identify singular and plural",
          "Answer simple oral questions",
        ],
        g3SLOs: [
          "Recite Hamd with rhythm",
          "Learn 8 vocabulary words",
          "Identify حروف جر",
          "Write 4–5 sentences using new vocabulary",
        ],
      },
    ],
  },

  Mathematics: {
    color: "#0d7c5f",
    light: "#d1fae5",
    emoji: "🔢",
    desc: "15 chapters · Numbers, Operations, Measurement, Geometry",
    lessonTypes: [
      "Number Concepts",
      "Operations & Calculation",
      "Word Problems",
      "Measurement",
      "Geometry & Data",
    ],
    chapters: [
      {
        id: "m1",
        name: "Ch.1 — Numbers & Place Value",
        align: "★★★★★",
        g2: "Numberland Adventures",
        g3: "Number Ninjas",
        g2SLOs: [
          "Count numbers up to 999",
          "Read and write 3-digit numbers",
          "Identify place value hundreds tens ones",
          "Compare numbers using < > =",
        ],
        g3SLOs: [
          "Count numbers up to 9999",
          "Read and write 4-digit numbers",
          "Identify thousands hundreds tens ones",
          "Write numbers in expanded form",
        ],
      },

      {
        id: "m2",
        name: "Ch.2 — Addition",
        align: "★★★★★",
        g2: "Add-It-Up Island",
        g3: "Addition Masters",
        g2SLOs: [
          "Add 3-digit numbers",
          "Add with regrouping",
          "Solve simple addition word problems",
        ],
        g3SLOs: [
          "Add 4-digit numbers",
          "Solve 2-step addition word problems",
          "Estimate sums by rounding",
        ],
      },

      {
        id: "m3",
        name: "Ch.3 — Subtraction",
        align: "★★★★★",
        g2: "Take Away Jungle",
        g3: "Subtraction Experts",
        g2SLOs: [
          "Subtract 3-digit numbers",
          "Subtract with regrouping",
          "Solve subtraction word problems",
        ],
        g3SLOs: [
          "Subtract 4-digit numbers",
          "Solve mixed operation word problems",
          "Check answers using addition",
        ],
      },

      {
        id: "m4",
        name: "Ch.4 — Multiplication",
        align: "★★★★☆",
        g2: "Magic Multiplication",
        g3: "Multiplication Mountain",
        g2SLOs: [
          "Learn tables 2–5 and 10",
          "Understand multiplication as repeated addition",
          "Solve simple multiplication word problems",
        ],
        g3SLOs: [
          "Learn tables 6–9",
          "Multiply 3-digit by 1-digit numbers",
          "Solve 2-step multiplication problems",
        ],
      },

      {
        id: "m5",
        name: "Ch.5 — Division",
        align: "★★★★★",
        g2: "Divide and Share",
        g3: "Division Masters",
        g2SLOs: [
          "Understand division as sharing",
          "Divide 2-digit numbers by 1-digit",
          "Connect division with multiplication",
          "Solve simple division word problems",
        ],
        g3SLOs: [
          "Divide 3-digit numbers by 1-digit",
          "Understand remainders",
          "Solve division word problems",
        ],
      },
    ],
  },
};
