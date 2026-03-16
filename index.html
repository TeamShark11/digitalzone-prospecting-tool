import React, { useMemo, useState } from 'react';
import { motion } from 'framer-motion';
import { Search, Building2, Mail, Target, TrendingUp, MessageSquare, Filter, Sparkles, BarChart3, User, Briefcase } from 'lucide-react';
import { Card, CardContent, CardHeader, CardTitle } from '@/components/ui/card';
import { Button } from '@/components/ui/button';
import { Input } from '@/components/ui/input';
import { Textarea } from '@/components/ui/textarea';
import { Badge } from '@/components/ui/badge';
import { Tabs, TabsContent, TabsList, TabsTrigger } from '@/components/ui/tabs';
import { Select, SelectContent, SelectItem, SelectTrigger, SelectValue } from '@/components/ui/select';
import { Progress } from '@/components/ui/progress';

const accountData = [
  {
    id: 1,
    company: 'Adobe',
    industry: 'Software',
    region: 'EMEA',
    contacts: 18,
    profileFit: 24,
    marketPriority: 22,
    intentStrength: 21,
    personaCoverage: 14,
    dataQuality: 9,
    score: 90,
    signals: ['Enterprise marketing team', 'High TAM fit', 'Strong persona mix'],
    whyNow: 'Good fit for enterprise demand generation, nurture, and persona-led outreach.',
    likelyPain: 'Scaling demand while improving visibility into which contacts are actually engaging.',
    recommendedAngle: 'Contact-level visibility and buying-group engagement reporting.',
    bestProof: 'We help enterprise tech teams move from broad targeting to real contact-level insight.',
  },
  {
    id: 2,
    company: 'Schneider Electric',
    industry: 'Industrial Tech',
    region: 'Global',
    contacts: 27,
    profileFit: 25,
    marketPriority: 23,
    intentStrength: 22,
    personaCoverage: 15,
    dataQuality: 10,
    score: 95,
    signals: ['Strategic enterprise account', 'Complex buying group', 'Multi-region relevance'],
    whyNow: 'Ideal fit for multi-touch, persona-based outreach with strong account depth.',
    likelyPain: 'Reaching technical and business stakeholders with the right message across long cycles.',
    recommendedAngle: 'Persona-based nurture plus contact-level account intelligence.',
    bestProof: 'Interactive nurture and account reporting can show exactly where momentum is building.',
  },
  {
    id: 3,
    company: 'CrowdStrike',
    industry: 'Cybersecurity',
    region: 'EMEA',
    contacts: 13,
    profileFit: 23,
    marketPriority: 19,
    intentStrength: 20,
    personaCoverage: 12,
    dataQuality: 8,
    score: 82,
    signals: ['Cybersecurity fit', 'Strong marketing persona relevance', 'Good audience depth'],
    whyNow: 'Cybersecurity teams often care about quality pipeline and signal clarity.',
    likelyPain: 'Understanding which contacts inside target accounts are actually moving toward intent.',
    recommendedAngle: 'Buying-group engagement and sales-usable journey visibility.',
    bestProof: 'We surface signals at contact level, not just vague account heatmaps.',
  },
  {
    id: 4,
    company: 'Qlik',
    industry: 'Data & Analytics',
    region: 'EMEA',
    contacts: 11,
    profileFit: 21,
    marketPriority: 17,
    intentStrength: 18,
    personaCoverage: 11,
    dataQuality: 8,
    score: 75,
    signals: ['Good software fit', 'Relevant marketing personas', 'Moderate account depth'],
    whyNow: 'Relevant for outreach where differentiation and audience penetration matter.',
    likelyPain: 'Turning awareness into qualified conversations with the right personas.',
    recommendedAngle: 'Programmatic nurture and persona-led messaging.',
    bestProof: 'Content-led outreach works better when you know which contacts actually consumed it.',
  },
  {
    id: 5,
    company: 'Red Hat',
    industry: 'Enterprise Software',
    region: 'UKI',
    contacts: 9,
    profileFit: 20,
    marketPriority: 16,
    intentStrength: 16,
    personaCoverage: 10,
    dataQuality: 7,
    score: 69,
    signals: ['Enterprise software fit', 'Relevant buying group', 'Needs more depth'],
    whyNow: 'Broad audience and layered buying committees make message relevance critical.',
    likelyPain: 'Maintaining relevance across multiple personas in long sales cycles.',
    recommendedAngle: 'Dynamic messaging by function and seniority.',
    bestProof: 'One message rarely fits a full buying group - persona adaptation matters.',
  },
];

const contactData = [
  {
    id: 101,
    name: 'Sarah Bennett',
    title: 'Director, Growth Marketing',
    function: 'Growth Marketing',
    level: 'Director',
    company: 'CrowdStrike',
    region: 'EMEA',
    email: 'sarah.bennett@crowdstrike.com',
    phone: '+44 20 7946 0123',
    linkedin: 'linkedin.com/in/sarah-bennett-growth',
  },
  {
    id: 102,
    name: 'Tom Alvarez',
    title: 'Senior Manager, Demand Generation',
    function: 'Demand Gen',
    level: 'Senior Manager',
    company: 'Adobe',
    region: 'EMEA',
    email: 'tom.alvarez@adobe.com',
    phone: '+44 20 7946 0456',
    linkedin: 'linkedin.com/in/tom-alvarez-demandgen',
  },
  {
    id: 103,
    name: 'Nina Hoffman',
    title: 'Global ABM Lead',
    function: 'ABM',
    level: 'Lead',
    company: 'Schneider Electric',
    region: 'Global',
    email: 'nina.hoffman@se.com',
    phone: '+33 1 73 28 20 00',
    linkedin: 'linkedin.com/in/nina-hoffman-abm',
  },
  {
    id: 104,
    name: 'David Ross',
    title: 'VP, Field Marketing',
    function: 'Field Marketing',
    level: 'VP',
    company: 'Qlik',
    region: 'EMEA',
    email: 'david.ross@qlik.com',
    phone: '+44 20 7946 0789',
    linkedin: 'linkedin.com/in/david-ross-fieldmarketing',
  },
];

const templates = {
  'Demand Gen': `Hi [First Name],\n\nI wanted to reach out because teams in [Industry] are under growing pressure to deliver quality pipeline, not just volume.\n\nAt Digitalzone, we help marketers understand which contacts inside target accounts are actually engaging across channels, so outreach and handoff to sales can be more precise.\n\nFor [Company], that could be especially relevant if you're looking to improve visibility into buying-group engagement across nurture, display, and content.\n\nWould it be worth comparing notes?\n\nBest,\nMartin\n\nP.S. Happy to share a quick example of how similar teams use contact-level reporting to sharpen follow-up.`,
  'Growth Marketing': `Hi [First Name],\n\nOne thing we hear a lot from growth teams is that there are more touches than ever, but not always more clarity on who inside an account is actually moving.\n\nDigitalzone helps solve that by pairing audience reach with contact-level journey visibility, making it easier to prioritize accounts and follow-up messaging.\n\nGiven [Company]'s focus, I thought this might be relevant.\n\nOpen to a quick chat?\n\nBest,\nMartin\n\nP.S. I can also share a few messaging angles that tend to resonate with similar teams.`,
  'ABM': `Hi [First Name],\n\nABM works best when sales and marketing can see more than just account-level engagement.\n\nWe support teams with contact-level insight across target accounts, helping them understand which personas are active, what they engaged with, and where momentum is building.\n\nThat often makes follow-up more relevant and conversion-friendly.\n\nWorth a conversation?\n\nBest,\nMartin\n\nP.S. We can usually spot where buying-group depth is strong versus where coverage is still thin.`,
  'Field Marketing': `Hi [First Name],\n\nA lot of field teams are being asked to prove local and regional impact more clearly, especially across larger enterprise programs.\n\nDigitalzone helps by combining targeted reach with contact-level engagement visibility, so regional follow-up is driven by real signals instead of guesswork.\n\nThought this might be useful for [Company].\n\nWould a short intro call be relevant?\n\nBest,\nMartin\n\nP.S. Happy to send over a short benchmark first if easier.`,
};

const performanceData = [
  { angle: 'Buying-group visibility', replyRate: 17, meetings: 9 },
  { angle: 'Pipeline quality', replyRate: 12, meetings: 6 },
  { angle: 'Persona-led nurture', replyRate: 10, meetings: 4 },
  { angle: 'Contact-level reporting', replyRate: 19, meetings: 11 },
];

function scoreLabel(score) {
  if (score >= 90) return 'Tier 1';
  if (score >= 80) return 'Tier 2';
  if (score >= 70) return 'Tier 3';
  return 'Tier 4';
}

function calculateIndustryScore(row, weights = { profileFit: 25, marketPriority: 25, intentStrength: 25, personaCoverage: 15, dataQuality: 10 }) {
  const profileFit = Number(row.profileFit || row['Profile Fit'] || 0);
  const marketPriority = Number(row.marketPriority || row['Market Priority'] || 0);
  const intentStrength = Number(row.intentStrength || row['Intent Strength'] || 0);
  const personaCoverage = Number(row.personaCoverage || row['Persona Coverage'] || 0);
  const dataQuality = Number(row.dataQuality || row['Data Quality'] || 0);

  const weightedScore =
    (profileFit / 25) * weights.profileFit +
    (marketPriority / 25) * weights.marketPriority +
    (intentStrength / 25) * weights.intentStrength +
    (personaCoverage / 15) * weights.personaCoverage +
    (dataQuality / 10) * weights.dataQuality;

  return Math.round(weightedScore);
}

function generateAngles(contact, account) {
  return [
    {
      title: 'Why now',
      text: `${account.company} appears to be in a phase where message relevance and buying-group reach matter. A strong opener is around ${account.likelyPain.toLowerCase()}`,
    },
    {
      title: 'What to say',
      text: `Lead with ${account.recommendedAngle.toLowerCase()} and keep it tied to ${contact.function.toLowerCase()} priorities.`,
    },
    {
      title: 'Proof point',
      text: account.bestProof,
    },
  ];
}

export default function DigitalzoneOutreachIntelligenceApp() {
  const [search, setSearch] = useState('');
  const [selectedAccountId, setSelectedAccountId] = useState(accountData[0].id);
  const [selectedContactId, setSelectedContactId] = useState(contactData[1].id);
  const [customContext, setCustomContext] = useState('Need a concise, contextual first-touch email that feels relevant to their role and current priorities.');
  const [industryFilter, setIndustryFilter] = useState('All');
  const [uploadedRows, setUploadedRows] = useState([]);
  const [bulkMessages, setBulkMessages] = useState([]);
  const [activeTab, setActiveTab] = useState('accounts');
  const [scoreWeights, setScoreWeights] = useState({
    profileFit: 25,
    marketPriority: 25,
    intentStrength: 25,
    personaCoverage: 15,
    dataQuality: 10,
  });

  const filteredAccounts = useMemo(() => {
    return accountData
      .filter((a) => industryFilter === 'All' || a.industry === industryFilter)
      .filter((a) => {
        const term = search.toLowerCase();
        return !term || a.company.toLowerCase().includes(term) || a.industry.toLowerCase().includes(term) || a.region.toLowerCase().includes(term);
      })
      .sort((a, b) => b.score - a.score);
  }, [search, industryFilter]);

  const selectedAccount = accountData.find((a) => a.id === selectedAccountId) || accountData[0];
  const selectedContact = contactData.find((c) => c.id === selectedContactId) || contactData[0];
  const relevantTemplate = templates[selectedContact.function] || templates['Demand Gen'];

  const generatedEmail = relevantTemplate
    .replaceAll('[First Name]', selectedContact.name.split(' ')[0])
    .replaceAll('[Company]', selectedAccount.company)
    .replaceAll('[Industry]', selectedAccount.industry)
    + `

Context note for outreach:
${customContext}`;

  const angles = generateAngles(selectedContact, selectedAccount);

  const totals = {
    accounts: accountData.length,
    contacts: accountData.reduce((sum, a) => sum + a.contacts, 0),
    avgScore: Math.round(accountData.reduce((sum, a) => sum + a.score, 0) / accountData.length),
    bestReplyRate: Math.max(...performanceData.map((d) => d.replyRate)),
  };

  const rescoredUploadedRows = useMemo(() => {
    return uploadedRows.map((row) => ({
      ...row,
      score: calculateIndustryScore(row, scoreWeights),
    }));
  }, [uploadedRows, scoreWeights]);

  const parseCsvText = (text) => {
    const lines = text.split(/
?
/).filter(Boolean);
    if (lines.length < 2) return [];
    const headers = lines[0].split(',').map((h) => h.trim());
    return lines.slice(1).map((line, index) => {
      const values = line.split(',');
      const row = { id: `upload-${index + 1}` };
      headers.forEach((header, i) => {
        row[header] = (values[i] || '').trim();
      });
      row.score = calculateIndustryScore(row, scoreWeights);
      return row;
    });
  };

  const handleCsvUpload = (event) => {
    const file = event.target.files?.[0];
    if (!file) return;
    const reader = new FileReader();
    reader.onload = (e) => {
      const text = String(e.target?.result || '');
      const rows = parseCsvText(text);
      setUploadedRows(rows);
      setActiveTab('bulk');
    };
    reader.readAsText(file);
  };

  const buildBulkMessages = () => {
    const messages = rescoredUploadedRows.map((row, index) => {
      const firstName = row.firstName || row.FirstName || row.Name || row['First Name'] || 'there';
      const company = row.company || row.Company || 'your team';
      const title = row.title || row.Title || row['Job Title'] || 'marketing leader';
      const functionName = row.function || row.Function || 'Demand Gen';
      const industry = row.industry || row.Industry || 'your industry';
      const region = row.region || row.Region || 'Unknown region';
      const email = row.email || row.Email || row['E-mail'] || '';
      const phone = row.phone || row.Phone || '';
      const linkedin = row.linkedin || row.LinkedIn || row['LI Profile'] || row['LinkedIn Profile'] || '';
      const template = templates[functionName] || templates['Demand Gen'];
      const body = template
        .replaceAll('[First Name]', firstName)
        .replaceAll('[Company]', company)
        .replaceAll('[Industry]', industry)
        + `

Context note for outreach:
Tailor this for ${title} with a sharper point around conversion, relevant engagement, and account visibility.`;
      return {
        id: index + 1,
        name: firstName,
        company,
        title,
        functionName,
        region,
        email,
        phone,
        linkedin,
        score: row.score || calculateIndustryScore(row, scoreWeights),
        body,
      };
    });
    setBulkMessages(messages);
  };

  // --- Export helpers ---
  const exportCsv = () => {
    if (!bulkMessages.length) return;
    const headers = ["Name","Company","Title","Region","Email","Phone","LinkedIn","Score","Message"];
    const rows = bulkMessages.map(m => [m.name,m.company,m.title,m.region,m.email,m.phone,m.linkedin,m.score,(m.body||"").replace(/
/g,' ')]);
    const csv = [headers,...rows].map(r=>r.map(v=>`"${String(v||"").replace(/"/g,'""')}"`).join(",")).join("
");
    const blob = new Blob([csv],{type:"text/csv"});
    const url = URL.createObjectURL(blob);
    const a = document.createElement("a");
    a.href = url;
    a.download = "digitalzone_outreach_drafts.csv";
    a.click();
    URL.revokeObjectURL(url);
  };

  // Simple filters for large lists
  const [filterRegion,setFilterRegion] = useState('All');
  const [filterFunction,setFilterFunction] = useState('All');
  const [linkedinPaste, setLinkedinPaste] = useState('');
  const [linkedinProfile, setLinkedinProfile] = useState(null);
  const [selectedResearchCompany, setSelectedResearchCompany] = useState('Adobe');
  const [crmStatusFilter, setCrmStatusFilter] = useState('All');
  const [contactStatuses, setContactStatuses] = useState({});

  const filteredBulkMessages = useMemo(()=>{
    return bulkMessages.filter(m=>{
      if(filterRegion!== 'All' && m.region!==filterRegion) return false;
      if(filterFunction!== 'All' && m.functionName!==filterFunction) return false;
      const currentStatus = contactStatuses[m.id] || 'Not Contacted';
      if(crmStatusFilter !== 'All' && currentStatus !== crmStatusFilter) return false;
      return true;
    });
  },[bulkMessages,filterRegion,filterFunction,crmStatusFilter,contactStatuses]);

  const companyResearch = {
    Adobe: {
      priorities: ['Enterprise pipeline quality', 'Regional demand scale', 'Buying-group visibility'],
      painPoints: ['Lead volume without enough context', 'Long buying cycles', 'Pressure to prove marketing contribution'],
      proofPoints: ['Contact-level engagement reporting', 'Persona-led nurture', 'Audience penetration across regions'],
      questions: ['How are you prioritising which contacts inside target accounts are actually ready for follow-up?', 'Where do you feel blind spots still exist between campaign engagement and sales action?', 'How are you measuring buying-group depth, not just individual responses?'],
    },
    'Schneider Electric': {
      priorities: ['Complex audience education', 'Account penetration', 'Cross-region message relevance'],
      painPoints: ['Technical plus business buying groups', 'Long enterprise consideration cycles', 'Need for clearer contact-level momentum'],
      proofPoints: ['Multi-touch nurture', 'Interactive experiences', 'Contact-level and account-level reporting'],
      questions: ['Which personas are hardest to reach consistently today?', 'How do you currently see momentum building across multiple stakeholders?', 'Where would more precise follow-up data help your team most?'],
    },
    CrowdStrike: {
      priorities: ['Quality pipeline', 'Conversion efficiency', 'Growth visibility'],
      painPoints: ['Crowded market', 'Signal overload', 'Need for more sales-usable context'],
      proofPoints: ['Buying-group engagement insights', 'Journey visibility', 'Role-based messaging'],
      questions: ['What signals actually help your team decide where to follow up?', 'How do you avoid treating engaged accounts as a black box?', 'How much visibility do sellers have into which personas engaged with what?'],
    },
    Qlik: {
      priorities: ['Differentiated outreach', 'Audience quality', 'Thought leadership conversion'],
      painPoints: ['Busy category', 'Message relevance', 'Turning content engagement into meetings'],
      proofPoints: ['Persona-led outreach', 'Programmatic nurture', 'Contact-level reporting'],
      questions: ['Which personas convert best once they engage?', 'How are you connecting content consumption to actual pipeline conversations?', 'Where are you losing momentum between interest and action?'],
    },
    'Red Hat': {
      priorities: ['Enterprise reach', 'Partner ecosystem influence', 'Long-cycle engagement'],
      painPoints: ['Many stakeholders', 'Different persona needs', 'Need for better prioritisation'],
      proofPoints: ['Function-based messaging', 'Buying-group visibility', 'Better list quality and segmentation'],
      questions: ['How do you currently adapt messaging by function or seniority?', 'Where do you see the biggest drop-off in long buying journeys?', 'How are you identifying which accounts deserve more sales time?'],
    },
  };

  const handleLinkedinGenerate = () => {
    const slug = linkedinPaste.trim().split('/').filter(Boolean).pop() || 'prospect';
    const clean = slug.replace(/[-_]/g, ' ').replace(/\?.*/, '');
    const name = clean.split(' ').map(part => part.charAt(0).toUpperCase() + part.slice(1)).join(' ');
    const profile = {
      name,
      title: 'Marketing Leader',
      company: selectedResearchCompany,
      region: 'EMEA',
      summary: `Likely a relevant stakeholder at ${selectedResearchCompany} based on the LinkedIn profile pasted.`,
      message: `Hi ${name.split(' ')[0]},

I came across your profile and thought it could be relevant to reach out. At Digitalzone, we help teams like ${selectedResearchCompany} improve outreach by showing which contacts inside target accounts are actually engaging across channels - making follow-up more relevant and conversion-friendly.

Would it be useful to compare notes?

Best,
Martin

P.S. Happy to share a short example tied to account visibility and persona engagement.`,
    };
    setLinkedinProfile(profile);
    setActiveTab('linkedin');
  };

  const setStatus = (id, status) => {
    setContactStatuses((prev) => ({ ...prev, [id]: status }));
  };

  return (
    <div className="min-h-screen bg-slate-50 p-6">
      <div className="mx-auto max-w-7xl space-y-6">
        <motion.div
          initial={{ opacity: 0, y: 10 }}
          animate={{ opacity: 1, y: 0 }}
          className="grid gap-4 md:grid-cols-[1.8fr_1fr]"
        >
          <Card className="rounded-2xl shadow-sm border-0">
            <CardContent className="p-6">
              <div className="flex items-start justify-between gap-4">
                <div>
                  <div className="flex items-center gap-2 text-sm text-slate-500 mb-2">
                    <Sparkles className="h-4 w-4" />
                    Digitalzone outreach intelligence MVP
                  </div>
                  <h1 className="text-3xl font-semibold tracking-tight text-slate-900">Contextual outreach and account prioritisation</h1>
                  <p className="mt-2 text-sm text-slate-600 max-w-3xl">
                    A working prototype for ranking accounts, surfacing outreach context, generating relevant first-touch messaging, and now handling CSV upload plus bulk message generation.
                  </p>
                </div>
                <div className="flex gap-2">
                  <div className="flex gap-2">
                  <Button className="rounded-2xl" onClick={buildBulkMessages}>Generate bulk copy</Button>
                  <Button className="rounded-2xl" onClick={exportCsv}>Export CSV</Button>
                </div>
                </div>
              </div>
            </CardContent>
          </Card>

          <div className="grid grid-cols-2 gap-4">
            <Card className="rounded-2xl shadow-sm border-0"><CardContent className="p-4"><div className="text-xs text-slate-500">Accounts</div><div className="mt-1 text-2xl font-semibold">{totals.accounts}</div></CardContent></Card>
            <Card className="rounded-2xl shadow-sm border-0"><CardContent className="p-4"><div className="text-xs text-slate-500">Contacts</div><div className="mt-1 text-2xl font-semibold">{totals.contacts}</div></CardContent></Card>
            <Card className="rounded-2xl shadow-sm border-0"><CardContent className="p-4"><div className="text-xs text-slate-500">Uploaded rows</div><div className="mt-1 text-2xl font-semibold">{uploadedRows.length}</div></CardContent></Card>
            <Card className="rounded-2xl shadow-sm border-0"><CardContent className="p-4"><div className="text-xs text-slate-500">Bulk drafts</div><div className="mt-1 text-2xl font-semibold">{bulkMessages.length}</div></CardContent></Card>
          </div>
        </motion.div>

        <Tabs value={activeTab} onValueChange={setActiveTab} className="space-y-4">
          <TabsList className="grid w-full max-w-6xl grid-cols-8 rounded-2xl">
            <TabsTrigger value="accounts">Accounts</TabsTrigger>
            <TabsTrigger value="messages">Messages</TabsTrigger>
            <TabsTrigger value="contacts">Contacts</TabsTrigger>
            <TabsTrigger value="performance">Performance</TabsTrigger>
            <TabsTrigger value="bulk">Bulk</TabsTrigger>
            <TabsTrigger value="scoring">Scoring</TabsTrigger>
            <TabsTrigger value="research">Research</TabsTrigger>
            <TabsTrigger value="linkedin">LinkedIn</TabsTrigger>
          </TabsList>

          <TabsContent value="accounts" className="grid gap-6 lg:grid-cols-[1.05fr_1.3fr]">
            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><Target className="h-5 w-5" /> Priority accounts</CardTitle>
              </CardHeader>
              <CardContent className="space-y-4">
                <div className="flex flex-col gap-3 md:flex-row">
                  <div className="relative flex-1">
                    <Search className="absolute left-3 top-3 h-4 w-4 text-slate-400" />
                    <Input value={search} onChange={(e) => setSearch(e.target.value)} placeholder="Search company, industry, region" className="pl-9 rounded-2xl" />
                  </div>
                  <Select value={industryFilter} onValueChange={setIndustryFilter}>
                    <SelectTrigger className="w-full md:w-52 rounded-2xl">
                      <div className="flex items-center gap-2"><Filter className="h-4 w-4" /><SelectValue placeholder="Industry" /></div>
                    </SelectTrigger>
                    <SelectContent>
                      <SelectItem value="All">All industries</SelectItem>
                      {Array.from(new Set(accountData.map((a) => a.industry))).map((industry) => (
                        <SelectItem key={industry} value={industry}>{industry}</SelectItem>
                      ))}
                    </SelectContent>
                  </Select>
                </div>

                <div className="space-y-3 max-h-[560px] overflow-auto pr-1">
                  {filteredAccounts.map((account) => (
                    <button
                      key={account.id}
                      onClick={() => setSelectedAccountId(account.id)}
                      className={`w-full rounded-2xl border p-4 text-left transition ${selectedAccountId === account.id ? 'border-slate-900 bg-white shadow-sm' : 'border-slate-200 bg-slate-50 hover:bg-white'}`}
                    >
                      <div className="flex items-start justify-between gap-3">
                        <div>
                          <div className="font-semibold text-slate-900">{account.company}</div>
                          <div className="text-xs text-slate-500 mt-1">{account.industry} - {account.region}</div>
                        </div>
                        <Badge variant="secondary">{scoreLabel(account.score)}</Badge>
                      </div>
                      <div className="mt-3 flex items-center gap-3 text-sm text-slate-600">
                        <span>Score {account.score}</span>
                        <span>•</span>
                        <span>{account.contacts} contacts</span>
                      </div>
                      <Progress value={account.score} className="mt-3 h-2" />
                      <div className="mt-3 flex flex-wrap gap-2">
                        {account.signals.map((signal) => (
                          <Badge key={signal} variant="outline" className="rounded-xl">{signal}</Badge>
                        ))}
                      </div>
                    </button>
                  ))}
                </div>
              </CardContent>
            </Card>

            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><Building2 className="h-5 w-5" /> Account context</CardTitle>
              </CardHeader>
              <CardContent className="space-y-5">
                <div>
                  <div className="flex items-center justify-between gap-3">
                    <div>
                      <h2 className="text-2xl font-semibold">{selectedAccount.company}</h2>
                      <p className="text-sm text-slate-500 mt-1">{selectedAccount.industry} - {selectedAccount.region}</p>
                    </div>
                    <div className="text-right">
                      <div className="text-xs text-slate-500">Priority score</div>
                      <div className="text-3xl font-semibold">{selectedAccount.score}</div>
                    </div>
                  </div>
                </div>

                <div className="grid gap-4 md:grid-cols-2">
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500 mb-2">Why now</div><div className="text-sm text-slate-800">{selectedAccount.whyNow}</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500 mb-2">Scoring model</div><div className="text-sm text-slate-800">Profile fit {selectedAccount.profileFit}/25 - Market priority {selectedAccount.marketPriority}/25 - Intent strength {selectedAccount.intentStrength}/25 - Persona coverage {selectedAccount.personaCoverage}/15 - Data quality {selectedAccount.dataQuality}/10</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500 mb-2">Likely pain point</div><div className="text-sm text-slate-800">{selectedAccount.likelyPain}</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500 mb-2">Recommended angle</div><div className="text-sm text-slate-800">{selectedAccount.recommendedAngle}</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500 mb-2">Best proof point</div><div className="text-sm text-slate-800">{selectedAccount.bestProof}</div></CardContent></Card>
                </div>
              </CardContent>
            </Card>
          </TabsContent>

          <TabsContent value="messages" className="grid gap-6 lg:grid-cols-[0.95fr_1.35fr]">
            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><MessageSquare className="h-5 w-5" /> Message generator</CardTitle>
              </CardHeader>
              <CardContent className="space-y-4">
                <div>
                  <label className="text-sm font-medium">Select account</label>
                  <Select value={String(selectedAccountId)} onValueChange={(v) => setSelectedAccountId(Number(v))}>
                    <SelectTrigger className="mt-2 rounded-2xl"><SelectValue /></SelectTrigger>
                    <SelectContent>
                      {accountData.map((a) => <SelectItem key={a.id} value={String(a.id)}>{a.company}</SelectItem>)}
                    </SelectContent>
                  </Select>
                </div>
                <div>
                  <label className="text-sm font-medium">Select contact</label>
                  <Select value={String(selectedContactId)} onValueChange={(v) => setSelectedContactId(Number(v))}>
                    <SelectTrigger className="mt-2 rounded-2xl"><SelectValue /></SelectTrigger>
                    <SelectContent>
                      {contactData.map((c) => <SelectItem key={c.id} value={String(c.id)}>{c.name} - {c.company}</SelectItem>)}
                    </SelectContent>
                  </Select>
                </div>
                <div>
                  <label className="text-sm font-medium">Outreach context</label>
                  <Textarea value={customContext} onChange={(e) => setCustomContext(e.target.value)} className="mt-2 min-h-[140px] rounded-2xl" />
                </div>

                <div className="space-y-3">
                  {angles.map((angle) => (
                    <Card key={angle.title} className="rounded-2xl bg-slate-50 border-0 shadow-none">
                      <CardContent className="p-4">
                        <div className="text-sm font-medium">{angle.title}</div>
                        <div className="text-sm text-slate-600 mt-2">{angle.text}</div>
                      </CardContent>
                    </Card>
                  ))}
                </div>
              </CardContent>
            </Card>

            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><Mail className="h-5 w-5" /> Generated first-touch email</CardTitle>
              </CardHeader>
              <CardContent>
                <div className="rounded-2xl bg-slate-50 p-4 whitespace-pre-wrap text-sm leading-6 text-slate-800 min-h-[560px]">{generatedEmail}</div>
              </CardContent>
            </Card>
          </TabsContent>

          <TabsContent value="contacts" className="grid gap-6 lg:grid-cols-[1fr_1.2fr]">
            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><User className="h-5 w-5" /> Contact list</CardTitle>
              </CardHeader>
              <CardContent className="space-y-3">
                {contactData.map((contact) => (
                  <button key={contact.id} onClick={() => setSelectedContactId(contact.id)} className={`w-full rounded-2xl border p-4 text-left transition ${selectedContactId === contact.id ? 'border-slate-900 bg-white shadow-sm' : 'border-slate-200 bg-slate-50 hover:bg-white'}`}>
                    <div className="font-semibold">{contact.name}</div>
                    <div className="text-sm text-slate-600 mt-1">{contact.title}</div>
                    <div className="text-xs text-slate-500 mt-2">{contact.company} - {contact.region}</div>
                  </button>
                ))}
              </CardContent>
            </Card>

            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><Briefcase className="h-5 w-5" /> Contact context</CardTitle>
              </CardHeader>
              <CardContent className="space-y-4">
                <div className="grid gap-4 md:grid-cols-2">
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500">Name</div><div className="mt-1 font-medium">{selectedContact.name}</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500">Job title</div><div className="mt-1 font-medium">{selectedContact.title}</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500">Region</div><div className="mt-1 font-medium">{selectedContact.region}</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500">Function</div><div className="mt-1 font-medium">{selectedContact.function}</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500">E-mail</div><div className="mt-1 font-medium break-all">{selectedContact.email}</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500">Phone</div><div className="mt-1 font-medium">{selectedContact.phone}</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none md:col-span-2"><CardContent className="p-4"><div className="text-xs text-slate-500">LinkedIn profile</div><div className="mt-1 font-medium break-all">{selectedContact.linkedin}</div></CardContent></Card>
                </div>

                <Card className="rounded-2xl border-0 bg-white shadow-sm">
                  <CardContent className="p-5">
                    <div className="text-sm font-medium">Suggested talk track</div>
                    <div className="mt-3 text-sm text-slate-700 leading-6">
                      Tie the conversation to {selectedContact.function.toLowerCase()} priorities, avoid generic lead-volume language, and focus on how better contact-level visibility can make sales follow-up more relevant and conversion-friendly.
                    </div>
                  </CardContent>
                </Card>
              </CardContent>
            </Card>
          </TabsContent>

          <TabsContent value="performance">
            <div className="grid gap-6 lg:grid-cols-[1.1fr_0.9fr]">
              <Card className="rounded-2xl shadow-sm border-0">
                <CardHeader>
                  <CardTitle className="flex items-center gap-2"><BarChart3 className="h-5 w-5" /> Messaging performance</CardTitle>
                </CardHeader>
                <CardContent className="space-y-4">
                  {performanceData.map((row) => (
                    <div key={row.angle} className="rounded-2xl bg-slate-50 p-4">
                      <div className="flex items-center justify-between gap-3">
                        <div>
                          <div className="font-medium">{row.angle}</div>
                          <div className="text-xs text-slate-500 mt-1">Meetings created: {row.meetings}</div>
                        </div>
                        <div className="text-right">
                          <div className="text-xs text-slate-500">Reply rate</div>
                          <div className="text-xl font-semibold">{row.replyRate}%</div>
                        </div>
                      </div>
                      <Progress value={row.replyRate * 4} className="mt-3 h-2" />
                    </div>
                  ))}
                </CardContent>
              </Card>

              <Card className="rounded-2xl shadow-sm border-0">
                <CardHeader>
                  <CardTitle className="flex items-center gap-2"><TrendingUp className="h-5 w-5" /> What is working</CardTitle>
                </CardHeader>
                <CardContent className="space-y-4 text-sm text-slate-700 leading-6">
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4">Messages tied to contact-level reporting and buying-group visibility are performing best in this mockup.</CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4">The more directly the message connects to the contact's role, the stronger the expected conversion rate.</CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4">A natural next version would add real CRM syncing, live scoring, and saved account playbooks.</CardContent></Card>
                </CardContent>
              </Card>
            </div>
          </TabsContent>

          <TabsContent value="bulk" className="grid gap-6 lg:grid-cols-[0.9fr_1.1fr]">
            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><Filter className="h-5 w-5" /> CSV upload and generation</CardTitle>
              </CardHeader>
              <CardContent className="space-y-4">
                <div className="rounded-2xl border border-dashed border-slate-300 bg-slate-50 p-5">
                  <div className="text-sm font-medium">Upload a CSV</div>
                  <div className="text-xs text-slate-500 mt-2">Expected columns: Name or First Name, Job Title, Region, E-mail, Phone, LinkedIn Profile or LI Profile, Company, Function, Industry, plus optional scoring inputs like Profile Fit, Market Priority, Intent Strength, Persona Coverage, and Data Quality.</div>
                  <Input type="file" accept=".csv" onChange={handleCsvUpload} className="mt-4 rounded-2xl bg-white" />
                </div>

                <Card className="rounded-2xl bg-slate-50 border-0 shadow-none">
                  <CardContent className="p-4 text-sm text-slate-700 leading-6">
                    Upload a contact list, then generate first-touch drafts in bulk. This is ideal for turning a spreadsheet of accounts into usable outreach copy much faster.
                  </CardContent>
                </Card>

                <Button className="w-full rounded-2xl" onClick={buildBulkMessages} disabled={!rescoredUploadedRows.length}>Generate messages from uploaded rows</Button>

                <div className="space-y-3 max-h-[340px] overflow-auto pr-1">
                  {rescoredUploadedRows.map((row, index) => (
                    <div key={row.id || index} className="rounded-2xl border border-slate-200 bg-white p-4">
                      <div className="font-medium">{row.Name || row['First Name'] || row.firstName || 'Unknown contact'}</div>
                      <div className="text-xs text-slate-500 mt-1">{row.Company || row.company || 'Unknown company'} - {row['Job Title'] || row.Title || row.title || 'Unknown title'}</div>
                      <div className="text-xs text-slate-500 mt-1">{row.Region || row.region || 'Unknown region'} - Score {row.score}</div>
                    </div>
                  ))}
                </div>
              </CardContent>
            </Card>

            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><Mail className="h-5 w-5" /> Bulk drafts</CardTitle>
              </CardHeader>
              <CardContent className="space-y-4 max-h-[700px] overflow-auto pr-1">
                <div className="flex gap-3">
                  <Select value={filterRegion} onValueChange={setFilterRegion}>
                    <SelectTrigger className="w-40 rounded-2xl"><SelectValue placeholder="Region"/></SelectTrigger>
                    <SelectContent>
                      <SelectItem value="All">All regions</SelectItem>
                      {[...new Set(bulkMessages.map(m=>m.region).filter(Boolean))].map(r=>(<SelectItem key={r} value={r}>{r}</SelectItem>))}
                    </SelectContent>
                  </Select>

                  <Select value={filterFunction} onValueChange={setFilterFunction}>
                    <SelectTrigger className="w-48 rounded-2xl"><SelectValue placeholder="Function"/></SelectTrigger>
                    <SelectContent>
                      <SelectItem value="All">All functions</SelectItem>
                      {[...new Set(bulkMessages.map(m=>m.functionName).filter(Boolean))].map(f=>(<SelectItem key={f} value={f}>{f}</SelectItem>))}
                    </SelectContent>
                  </Select>
                </div>
                {!bulkMessages.length && (
                  <div className="rounded-2xl bg-slate-50 p-5 text-sm text-slate-600">
                    No bulk drafts yet. Upload a CSV and generate messages to populate this view.
                  </div>
                )}
                {filteredBulkMessages.map((message) => (
                  <Card key={message.id} className="rounded-2xl bg-slate-50 border-0 shadow-none">
                    <CardContent className="p-4">
                      <div className="flex items-start justify-between gap-3">
                        <div>
                          <div className="font-semibold">{message.name} - {message.company}</div>
                          <div className="text-xs text-slate-500 mt-1">{message.title} - {message.functionName} - {message.region}</div>
                          <div className="text-xs text-slate-500 mt-1 break-all">{message.email} {message.phone ? `- ${message.phone}` : ''}</div>
                          <div className="text-xs text-slate-500 mt-1 break-all">{message.linkedin}</div>
                        </div>
                        <Badge variant="outline">Score {message.score}</Badge>
                      </div>
                      <div className="mt-4 whitespace-pre-wrap text-sm leading-6 text-slate-800">{message.body}</div>
                    </CardContent>
                  </Card>
                ))}
              </CardContent>
            </Card>
          </TabsContent>

          <TabsContent value="scoring" className="grid gap-6 lg:grid-cols-[0.95fr_1.05fr]">
            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><BarChart3 className="h-5 w-5" /> Editable scoring weights</CardTitle>
              </CardHeader>
              <CardContent className="space-y-5">
                <div>
                  <label className="text-sm font-medium">Profile fit</label>
                  <Input type="number" value={scoreWeights.profileFit} onChange={(e) => setScoreWeights({ ...scoreWeights, profileFit: Number(e.target.value || 0) })} className="mt-2 rounded-2xl" />
                  <div className="text-xs text-slate-500 mt-1">How closely the account matches your ICP, solution fit, and commercial relevance.</div>
                </div>
                <div>
                  <label className="text-sm font-medium">Market priority</label>
                  <Input type="number" value={scoreWeights.marketPriority} onChange={(e) => setScoreWeights({ ...scoreWeights, marketPriority: Number(e.target.value || 0) })} className="mt-2 rounded-2xl" />
                  <div className="text-xs text-slate-500 mt-1">Use this for region, named-account priority, strategic segment, or target market importance.</div>
                </div>
                <div>
                  <label className="text-sm font-medium">Intent strength</label>
                  <Input type="number" value={scoreWeights.intentStrength} onChange={(e) => setScoreWeights({ ...scoreWeights, intentStrength: Number(e.target.value || 0) })} className="mt-2 rounded-2xl" />
                  <div className="text-xs text-slate-500 mt-1">Signals like engagement, active campaigns, known initiatives, or timing relevance.</div>
                </div>
                <div>
                  <label className="text-sm font-medium">Persona coverage</label>
                  <Input type="number" value={scoreWeights.personaCoverage} onChange={(e) => setScoreWeights({ ...scoreWeights, personaCoverage: Number(e.target.value || 0) })} className="mt-2 rounded-2xl" />
                  <div className="text-xs text-slate-500 mt-1">Whether you have enough of the buying group covered by useful contacts.</div>
                </div>
                <div>
                  <label className="text-sm font-medium">Data quality</label>
                  <Input type="number" value={scoreWeights.dataQuality} onChange={(e) => setScoreWeights({ ...scoreWeights, dataQuality: Number(e.target.value || 0) })} className="mt-2 rounded-2xl" />
                  <div className="text-xs text-slate-500 mt-1">Accuracy and completeness of e-mail, phone, LinkedIn, and supporting details.</div>
                </div>
              </CardContent>
            </Card>

            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><TrendingUp className="h-5 w-5" /> Live scoring preview</CardTitle>
              </CardHeader>
              <CardContent className="space-y-4">
                <Card className="rounded-2xl bg-slate-50 border-0 shadow-none">
                  <CardContent className="p-4 text-sm text-slate-700 leading-6">
                    Adjust the weights to reflect different motions - for example named-account focus, higher intent campaigns, or broader territory prospecting.
                  </CardContent>
                </Card>
                <div className="space-y-3 max-h-[520px] overflow-auto pr-1">
                  {rescoredUploadedRows.length > 0 ? rescoredUploadedRows.map((row, index) => (
                    <div key={row.id || index} className="rounded-2xl border border-slate-200 bg-white p-4">
                      <div className="flex items-start justify-between gap-3">
                        <div>
                          <div className="font-semibold">{row.Name || row['First Name'] || row.firstName || 'Unknown contact'}</div>
                          <div className="text-xs text-slate-500 mt-1">{row.Company || row.company || 'Unknown company'} - {row['Job Title'] || row.Title || row.title || 'Unknown title'}</div>
                          <div className="text-xs text-slate-500 mt-1">{row.Region || row.region || 'Unknown region'}</div>
                        </div>
                        <Badge variant="outline">Score {row.score}</Badge>
                      </div>
                    </div>
                  )) : accountData.map((account) => (
                    <div key={account.id} className="rounded-2xl border border-slate-200 bg-white p-4">
                      <div className="flex items-start justify-between gap-3">
                        <div>
                          <div className="font-semibold">{account.company}</div>
                          <div className="text-xs text-slate-500 mt-1">{account.industry} - {account.region}</div>
                        </div>
                        <Badge variant="outline">Score {calculateIndustryScore(account, scoreWeights)}</Badge>
                      </div>
                    </div>
                  ))}
                </div>
              </CardContent>
            </Card>
          </TabsContent>

          <TabsContent value="research" className="grid gap-6 lg:grid-cols-[0.85fr_1.15fr]">
            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><Building2 className="h-5 w-5" /> Company research and call prep</CardTitle>
              </CardHeader>
              <CardContent className="space-y-4">
                <div>
                  <label className="text-sm font-medium">Select company</label>
                  <Select value={selectedResearchCompany} onValueChange={setSelectedResearchCompany}>
                    <SelectTrigger className="mt-2 rounded-2xl"><SelectValue /></SelectTrigger>
                    <SelectContent>
                      {Object.keys(companyResearch).map((company) => (
                        <SelectItem key={company} value={company}>{company}</SelectItem>
                      ))}
                    </SelectContent>
                  </Select>
                </div>
                <Card className="rounded-2xl bg-slate-50 border-0 shadow-none">
                  <CardContent className="p-4 text-sm text-slate-700 leading-6">
                    Use this tab as your 10-second call prep area. Pick a company and get likely priorities, pains, proof points, and discovery questions you can use immediately.
                  </CardContent>
                </Card>
              </CardContent>
            </Card>

            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><Briefcase className="h-5 w-5" /> Live prep output</CardTitle>
              </CardHeader>
              <CardContent className="space-y-4">
                <div className="grid gap-4 md:grid-cols-2">
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500 mb-2">Likely priorities</div><div className="space-y-2 text-sm text-slate-800">{companyResearch[selectedResearchCompany].priorities.map((item) => <div key={item}>{item}</div>)}</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500 mb-2">Likely pain points</div><div className="space-y-2 text-sm text-slate-800">{companyResearch[selectedResearchCompany].painPoints.map((item) => <div key={item}>{item}</div>)}</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500 mb-2">Relevant proof points</div><div className="space-y-2 text-sm text-slate-800">{companyResearch[selectedResearchCompany].proofPoints.map((item) => <div key={item}>{item}</div>)}</div></CardContent></Card>
                  <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="text-xs text-slate-500 mb-2">Discovery questions</div><div className="space-y-2 text-sm text-slate-800">{companyResearch[selectedResearchCompany].questions.map((item) => <div key={item}>{item}</div>)}</div></CardContent></Card>
                </div>
              </CardContent>
            </Card>
          </TabsContent>

          <TabsContent value="linkedin" className="grid gap-6 lg:grid-cols-[0.9fr_1.1fr]">
            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><User className="h-5 w-5" /> LinkedIn paste to message</CardTitle>
              </CardHeader>
              <CardContent className="space-y-4">
                <div>
                  <label className="text-sm font-medium">LinkedIn profile URL</label>
                  <Input value={linkedinPaste} onChange={(e) => setLinkedinPaste(e.target.value)} placeholder="Paste a LinkedIn profile URL here" className="mt-2 rounded-2xl" />
                </div>
                <div>
                  <label className="text-sm font-medium">Target company context</label>
                  <Select value={selectedResearchCompany} onValueChange={setSelectedResearchCompany}>
                    <SelectTrigger className="mt-2 rounded-2xl"><SelectValue /></SelectTrigger>
                    <SelectContent>
                      {Object.keys(companyResearch).map((company) => (
                        <SelectItem key={company} value={company}>{company}</SelectItem>
                      ))}
                    </SelectContent>
                  </Select>
                </div>
                <Button className="rounded-2xl w-full" onClick={handleLinkedinGenerate}>Generate message from LinkedIn paste</Button>
                <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4 text-sm text-slate-700 leading-6">Paste a LinkedIn URL and the app turns it into a lightweight prospect card plus a first-touch message you can adapt fast.</CardContent></Card>
              </CardContent>
            </Card>

            <Card className="rounded-2xl shadow-sm border-0">
              <CardHeader>
                <CardTitle className="flex items-center gap-2"><Mail className="h-5 w-5" /> Generated LinkedIn outreach</CardTitle>
              </CardHeader>
              <CardContent>
                {!linkedinProfile ? (
                  <div className="rounded-2xl bg-slate-50 p-5 text-sm text-slate-600">No profile generated yet. Paste a LinkedIn profile URL and generate a message.</div>
                ) : (
                  <div className="space-y-4">
                    <Card className="rounded-2xl bg-slate-50 border-0 shadow-none"><CardContent className="p-4"><div className="font-semibold">{linkedinProfile.name}</div><div className="text-xs text-slate-500 mt-1">{linkedinProfile.title} - {linkedinProfile.company} - {linkedinProfile.region}</div><div className="text-sm text-slate-700 mt-3">{linkedinProfile.summary}</div></CardContent></Card>
                    <div className="rounded-2xl bg-slate-50 p-4 whitespace-pre-wrap text-sm leading-6 text-slate-800 min-h-[280px]">{linkedinProfile.message}</div>
                  </div>
                )}
              </CardContent>
            </Card>
          </TabsContent>
        </Tabs>
      </div>
    </div>
  );
}
